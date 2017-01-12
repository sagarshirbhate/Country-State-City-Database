[![Open Source Love](https://badges.frapsoft.com/os/v1/open-source.png?v=103)](https://github.com/ellerbrock/open-source-badges/)          [![MIT Licence](https://badges.frapsoft.com/os/mit/mit.png?v=103)](https://opensource.org/licenses/mit-license.php)

### Worlds All Countries , States and Cities in Single File (Less than 1.5 MB):

<sub>Names Of all Countries , States and cities are included in JSON , PLIST and XML Format</sub>
-
<sub>All data is present just you have to add file in your project and fetch it from file.</sub>
-
<sub>Their structure is like</sub>
-
* Country -> States -> Cities.

### Json Structure is As Follows,(Not Complete List Just Sample)
```javascript
{
"Countries":[
			{
            "CountryName":"India",
			"States":[
						{
                        "StateName":"Maharashtra",
						"Cities":[
								"Pune",
								"Nagpur",
								"Mumbai"
                                  ]
                         },
                         {
                         "StateName":"Kerala",
                         "Cities":[
                         			"Kochi",
                                    "Munnar"
                                  ]
                          }
                       ]
             },
             {
              "CountryName":"Australia",
			  "States":[
						{
                        "StateName":"Aukland",
						"Cities":[
								"GlenField",
								"Henderson",
									"MilFord"
                                  ]
                         },
                         {
                         "StateName":"Melbourne",
                         "Cities":[
                         			"Melbourne",
                                    "South Oakleigh"
                                  ]
                          }
                       ]
              }
           ]
      }
             
```

### XML Structure is As Follows,(Not Complete List Just Sample)
```javascript
<?xml version="1.0" encoding="UTF-8"?>
 <!DOCTYPE plist PUBLIC "-//Apple//DTD PLIST 1.0//EN" "http://www.apple.com/DTDs/PropertyList-1.0.dtd">
 <plist version="1.0">
 <dict>
	<key>Countries</key>
	<array>
        <dict>
            <key>CountryName</key>
            <string>India</string>
            <key>States</key>
                <array>
                    <dict>
                    <key>Cities</key>
                    <array>
                        <string>Pune</string>
                        <string>Nagpur</string>
                        <string>Mumbai</string>
                    </array>
                    <key>StateName</key>
                    <string>Maharashtra</string>
                    </dict>
                    <dict>
                    <key>Cities</key>
                    <array>
                        <string>Kochi</string>
                        <string>Munnar</string>
                    </array>
                    <key>StateName</key>
                    <string>Kerala</string>
                    </dict>
                </array>
        </dict>
        <dict>
            <key>CountryName</key>
            <string>India</string>
            <key>States</key>
            <array>
                <dict>
                <key>Cities</key>
                <array>
                    <string>Pune</string>
                    <string>Nagpur</string>
                    <string>Mumbai</string>
                </array>
                <key>StateName</key>
                <string>Maharashtra</string>
                </dict>
                <dict>
                <key>Cities</key>
                <array>
                    <string>Kochi</string>
                    <string>Munnar</string>
                </array>
                <key>StateName</key>
                <string>Kerala</string>
                </dict>
            </array>
        </dict>
    </array>
 </dict>
</plist>
```
### Plist Structure is As Follows,(Not Complete List Just Sample)
![ScreenShot](https://github.com/sagarshirbhate/Instagram-Feed-View/blob/master/1.gif)
<sub>Note :</sub>
- 
* This Free database dose not guarantee for the complete list of world countries, states and cities
* You can manually change the spelling mistakes, or add edit any records, which are not correct.


