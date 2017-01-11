# Worlds-All-City-Database

Names Of all Countries , States and cities are included in JSON , PLIST and XML Format.

All data is present just you have to add file in your project and fetch it from file.

Their structure is like :
Country -> States -> Cities.

Json Structure is As Follows,(Not Complete List Just Sample)
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
