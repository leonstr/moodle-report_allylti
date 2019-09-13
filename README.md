# Ally accessibility reporting tool

The Ally reporting tool (report_allylti) provides a site wide accessibility report which can be broken down by course.

## Installation

The Ally accessibility report can be downloaded from:
 
https://github.com/blackboard-open-source/moodle-report_allylti

The reporting tool should be located and named as:
 [yourmoodledir]/report/allylti
 
## Configuration

For the reporting tool to function it is necessary to download and configure the Ally admin tool:

https://github.com/blackboard-open-source/moodle-tool_ally

Instructions on how to do so are available in the README.md file for the admin tool.

## Usage

After the successful installation and configuration of Ally, the reporting tool is accessible via the Site
Administration menu:

Site administration > Reports > Accessibility

## Uninstall
Remove all the tool_ally, filter_ally and report_allylti plugins from the code.
 
Then you must go to:
 [yourmoodledir]/admin/plugins.php#plugin_type_cell_tool
 
Search for the removed plugins and click on uninstall.

## License for Ally accessibility report

© Blackboard Inc 2017

This program is free software: you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation, either version 3 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT ANY
WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A
PARTICULAR PURPOSE.  See the GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
this program.  If not, see <http://www.gnu.org/licenses/>.
