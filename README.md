# Overview

The project integrates plantuml into fitnesse wiki.

# Installation

Install Graphviz on machine where your Fitnesse is running.
Copy jar file from this project Releases to plugins directory of your Fitnesse.
Add following lines to plugins.properties of your Fitnesse
```
{{{
Plugins = com.github.sbellus.fitnesse.plantuml.PlantumlPlugin
}}} 
```

# Usage

After installation you should be able to use command on wiki
```
!startuml
fitnesse -> plantuml : generate
!enduml
```

The command !startuml has following syntax !startuml ["title"] [align] [width] [height]. 
* Title has to be surronded by "", 
* align can be one of
  * c - center
  * r - right
  * l - left
* width is width in pixels 
* height is height in pixels

