# Themed-Widgets
Qlik Sense UI Widgets supporting themes.

# Implementation
1. Download the themedwidgets.zip file (or the sample/test application below)
2. Open Dev-Hub from your Qlik Sense 3.0 (or higher) environment (Server or Desktop)
3. Select "Import Widget library" from the "Create New" menu in the upper-right corner of the Dev-Hub main page.
4. Select the zip file downloaded above. 

# Use
1. In any Qlik Sense 3.0 (or higher) app...
2. Enter in "Edit" mode of the page you want to use the widget.
3. From the Left Navigation bar, under "Custom Objects", "themedwidgets", drag the "Colorful KPI" widget on to your display.
4. Configure the dimensions and the settings to achieve the desired results

Configuration Options:
* Data - Add at least one, and up to 11 measures, using the standard measure dialogs.
* Appearence > General - It is recommended to turn off titles, but that is up to you.
* Appearance > Settings:
  * Separate Primary Measure - First measure in list, is separated from the rest. Otherwise, all measures are listed in the order they appear in the Data section.
  * Theme - Select one of the themes presented.
  * Primary Measure Color - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the Primary Measure Value.
  * Measure Color - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the Secondary Measure Value(s) or the full list values (when Separate Primary Measure is un-checked).
  * Label Color - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the color of all labels (Primary or Secondary).


# Optional Sample/Test Application
1. Download the sampleapp.zip
2. In Qlik Sense 3.0 (or higher) QMC, import the sampleapp.zip into your applications
3. Go to Qlik Sense Hub, in your "My Work" folder, open the app and view the sheet.

# Please help...
This is my first UI Widget so I would love to get feedback and suggestions, pleae provide them in the comments below. In particular, I am intersted in cross-browser support issues, improvements in the CSS/LESS logic to be more optimal, and recommendations around how you would like the KPI to behave better in your responsive environment testing (mobile, tablet, desktop, orientation, sizing, etc...).

# Remaining items, I would like to add for future versions...
See Github Issues

# License
Released under the MIT license.
