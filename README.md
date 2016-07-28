# Themed-Widgets
Qlik Sense UI Widgets supporting themes, here are a few examples of what you can achieve with this UI Widget...
![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/example1.png)

![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/example2.png)

# Implementation
> ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/import_widget.png)

1. Download the themedwidgets.zip [latest version](https://github.com/newmans99/Themed-Widgets/raw/master/themedwidgets.zip) file
2. Open Dev-Hub from your Qlik Sense 3.0 (or higher) environment (Server or Desktop)
3. Select "Import Widget library" from the "Create New" menu in the upper-right corner of the Dev-Hub main page.
4. Select the zip file downloaded above.
5. ALTERNATIVELY: Unzip the file into your Qlik Sense Extensions folder (server or desktop) in a directory called "themedwidgets". 

# Use
> ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/UI_add_widget.png)

1. In any Qlik Sense 3.0 (or higher) app...
2. Enter in "Edit" mode of the page you want to use the widget.
3. From the Left Navigation bar, under "Custom Objects", "Themed Widgets", drag the "Colorful KPI" or "Colorful KPI Dimensional" widget on to your sheet.
4. Configure the dimensions, measures, and other settings to achieve the desired results.

# Configuration:
Each widget in this library has a set of common properties and widget specific properties. See the configuration options below for details about each one.

## Common Options
> ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/UI_settings_common.png)
* **Appearence > General** - For display purposes, it is recommended to turn off titles, but that is up to you.
* **Appearance > Settings**:
  * **Theme** - Select one of the themes presented. See below for information about the themes.
  * **Measure Color** - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the Secondary Measure Value(s) or the full list values (when Separate Primary Measure is un-checked or for the Dimensional widget).
  * **Label Color** - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the color of all labels (Primary or Secondary or for the Dimensional widget).

## **Colorful KPI** widget Options:  
> ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/UI_settings.png)
* **Data** - Add at least one and up to 11 measures. Uses the standard Qlik Sense measure dialogs (including formatting).
* **Appearance > Settings**:
  * **Separate Primary Measure** - First measure in list, is separated from the rest. Otherwise, all measures are listed in the order they appear in the Data section.
  * **Primary Measure Color** - Use any CSS/LESS supported color code (hex, named, rgb, etc...) or provide an expression for the Primary Measure Value.
  * NOTE: See common options above for remaining options.
  
## **Colorful KPI Dimensional** widget Options:  
> ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/UI_settings_dimensional.png)
* **Data** - Add one dimension and one measure. Uses the standard Qlik Sense dimension/measure options (including formatting).
* **Sorting** - Provide sorting options. Uses the standard Qlik Sense sorting options.
* **Appearance > Settings**:
  * **Display Measure Label** - Shows the measure lable in the KPI, e.g., "Revenue".
  * **Display Dimension Value** - Shows the dimension value in the KPI, e.g., "John Doe".
  * **Display Dimension Label** - Shows the dimension lable in the KPI, e.g., "Customer"
  * NOTE: See common options above for remaining options.

## Default Themes:
These themes are from a customer specific implementation, however you can modify the source code of the widget and the widget properties dialog box to modify or add/remove themes using the Widget Editor in the Dev-Hub.
  > ![](https://raw.githubusercontent.com/newmans99/Themed-Widgets/master/img/UI_themes.png)

# Optional Sample/Test Application
1. After installing the widget...
2. Download the "Sample App.qvf" [latest version](https://github.com/newmans99/Themed-Widgets/raw/master/Sample App.qvf)
2. In Qlik Sense 3.0 (or higher) QMC, import the App into your applications
3. Go to Qlik Sense Hub, in your "My Work" folder, open the app and view the sheet.

# Please help...
This is my first publically shared UI Widget so I would love to get feedback and suggestions, pleae provide them in the comments below. In particular, I am intersted in cross-browser support issues, improvements in the CSS/LESS logic to be more optimal, and recommendations around how you would like the KPI to behave better in your responsive environment testing (mobile, tablet, desktop, orientation, sizing, etc...).

# Remaining items, I would like to add for future versions...
See Github Issues

# License
Released under the MIT license.
