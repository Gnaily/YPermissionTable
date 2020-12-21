# Template-maven-multi-module
Template for maven multi-module project

modules structure

    Project-pom
        |
        |__ xx-bom: manage inner modules version   
        |      |
        |      |__ xx-parent(import xx-depdencies):manage plugin dependencies  and profiles
        |            |
        |            |__ xx-x
        |            |
        |            |__ xx-y
        |
        |__ xx-depdencies: manage library dependencies version 
        |
