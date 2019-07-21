# Midifrak Components
## Directory Structure
Each component directory, no matter what type contains
| File           |      Purpose                   |
| -------------- |:------------------------------:|
| *comp.json*    |  Name and Manifest of files    |
| *files/*       |    Non-code files, e.g. Models |
| *code/*        | Built Code                     |
## Validate 
* To check the validity of the components, run `rdmd midifrak.d validate`
* To build all the visualizations and send to git `rdmd midifrak.d build`