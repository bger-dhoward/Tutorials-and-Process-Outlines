# Model Analysis using Ladybug within Rhino Inside Revit

### Initial Setup
* Install Ladybug tools
  * *Must be done seperately for Rhino 7 and Rhino Inside Revit if using both environments*
  * Download latest version from https://www.food4rhino.com/en/app/ladybug-tools, or use installer files located at **L:\Ballinger Dept Resources\Computational Design and Data\Ladybug\Installers**
  * Follow directions from https://github.com/ladybug-tools/lbt-grasshopper/wiki/1.1-Windows-Installation-Steps
* If planning to run more advanced analysis using Honeybee, install Radiance and OpenStudio per the directions above.
  * Note: These require IT Admin approval / credentials to run installers.  Contact Ballinger_IT <Ballinger_IT@Ballinger.com> or Ballinger_BIM_Support <Ballinger_BIM_Support@ballinger.com>
* **Optional** Install Bifocals to enable automatic node labels.
  
### Running Rhino.Inside.Revit
* Open Revit and project model.
* From Rhino.Inside tab in Revit, click Start button. Once Rhino loads, the other buttons on the ribbon will activate.
* Click the Rhino button to open the Rhino interface window and/or click the Grasshopper button to open a Grasshopper window.

### Bringing Revit Geometry into Rhino.Inside using Grasshopper
Revit geometry can be previewed in Rhino by using the Graphical Element parameter node from the Revit panel of the Params tab.  Right click the node to Set One or Set Multiple graphical elements from the Revit model.
