cmake_minimum_required(VERSION 3.20)
project(lingmo-icons VERSION 1.0.0 DESCRIPTION "Lingmo Icons" LANGUAGES NONE)

include(FeatureSummary)

install(DIRECTORY Crule DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
install(DIRECTORY Crule-dark DESTINATION ${CMAKE_INSTALL_PREFIX}/share/icons)
