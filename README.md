# APEC Homes

1. [API Documentation](#markdown-header-api-documentation)
1. [Authentication](#markdown-header-authentication)
1. [API](#markdown-header-api)
    - [Properties](#markdown-header-properties)
        + [Get All Properties](#markdown-header-get-all-properties)
        + [Get Unit](#markdown-header-get-unit)
        + [Get Single Property](#markdown-header-get-single-property)
    - [News & Updates](#markdown-header-news-&-updates)
        + [Get All News & Updates](#markdown-header-get-all-news-&-updates)
    - [Notifications](#markdown-header-notifications)
        + [Get All Notifications](#markdown-header-get-all-notifications)
        + [Read a notification](#markdown-header-read-a-notification)
    - [Loan Calculator](#markdown-header-loan-calculator)
        + [Get Loan Calculator Result](#markdown-header-get-loan-calculator-result)
    - [Office Address](#markdown-header-office-address)
        + [Get All Office Addresses](#markdown-header-get-all-office-addresses)
        + [Get Single Office Address](#markdown-header-get-single-office-address)


---

## API Documentation
Development: `https://apc.betaprojex.com/app/api`

---

### Authentication
#### Basic Auth

Authorization: `Basic YWRtaW46YXBlY2hvbWVz`  
x-api-key: `apechomesrandomapistring`

---

## API

---

#### Properties

---

##### Get All Properties
GET `https://apc.betaprojex.com/app/api/properties`
##### Response
```json
200 OK
{
    "data": [
        {
            "property_description": {
                "id": 168,
                "logo": "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483.png",
                "property_name": "Paragon Village",
                "location": "Cavite",
                "address": "<p>Brgy. San Agustin / Brgy. Cabuco, Trece Martires, Cavite</p>\n",
                "featured_photos": [
                    "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                    "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
                    "https://apc.betaprojex.com/wp-content/uploads/2019/01/home-bg001-1128x452.png"
                ],
                "total_area": "23.848",
                "no_of_units": "3,196",
                "description": "EXCEPTIONAL LIFE\nTHROUGH SIMPLE LIVING\nWe often times aspire for excellence in all we do. But excellence can be felt even if done in a simple and mild setting. Living may not be extravagant to be exceptional. In the simplest of things, excellence can be found. Experience this now at Paragon Village.\nWith homes depicting simplicity and comfort, you and your family will surely feel that homey atmosphere, perfect in nurturing your family’s well being. Now, that’s a new take in simple living. Truly, at Paragon Village, life can simply be exceptional.",
                "features_amenities": [
                    "Entrance Gate with Guardhouse",
                    "Multi-Purpose Hall",
                    "Playground",
                    "Basketball Court",
                    "Centralized Water Supply",
                    "Concrete Roads, Curbs and Gutters",
                    "Underground Drainage System"
                ],
                "licensed_details": "<p>HLURB LS NO. 032135<br />\nLAND DEVT: DECEMBER 31, 2018<br />\nMAXIMUM SELLING PRICE: P1,700,000.00 (H/L)<br />\nBP 220 | HLURB ADVERTISEMENT APPROVAL NO. AA-STR-071818-0234</p>\n"
            },
            "model_house": [
                {
                    "name": "Townhouse",
                    "featured_image": false,
                    "floor_area": "44",
                    "bedroom": "2",
                    "bathroom": "1",
                    "parking_space": "0"
                },
                {
                    "name": "Duplex (without garage)",
                    "featured_image": "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                    "floor_area": "44.5",
                    "bedroom": "2",
                    "bathroom": "1",
                    "parking_space": "0"
                }
            ],
            "gallery": [
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/home-bg001-1128x452.png"
            ],
            "site_plan": [
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg"
            ],
            "vicinity_map": {
                "lat": "14.2829325",
                "long": "120.8499808"
            }
        },
        {
            "property_description": {
                "id": 28,
                "logo": null,
                "property_name": "Highland Residences",
                "location": "",
                "address": "",
                "featured_photos": [
                    "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
                ],
                "total_area": "",
                "no_of_units": "",
                "description": "",
                "features_amenities": [
                    []
                ],
                "licensed_details": null
            },
            "model_house": [],
            "gallery": [
                "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
            ],
            "site_plan": [
                null
            ],
            "vicinity_map": {
                "lat": null,
                "long": null
            }
        },
        {
            "property_description": {
                "id": 21,
                "logo": null,
                "property_name": "Brixton Homes",
                "location": "",
                "address": "",
                "featured_photos": [
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/74994391_021728376-1.jpg",
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/IMG_5191.jpg",
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/slider3.jpg"
                ],
                "total_area": "1234",
                "no_of_units": "123",
                "description": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
                "features_amenities": [
                    []
                ],
                "licensed_details": null
            },
            "model_house": [],
            "gallery": [
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/74994391_021728376-1.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/IMG_5191.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/slider3.jpg"
            ],
            "site_plan": [
                null
            ],
            "vicinity_map": {
                "lat": null,
                "long": null
            }
        },
        {
            "property_description": {
                "id": 17,
                "logo": null,
                "property_name": "Southbrooke Village",
                "location": "Batangas",
                "address": "",
                "featured_photos": [
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/unnamed.jpg",
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/Wonderful-Panda-Wallpapers-HD-backgrounds.jpg",
                    "https://apc.betaprojex.com/wp-content/uploads/2018/11/Panda-Wallpapers-for-PC-Desktop.jpeg"
                ],
                "total_area": "543",
                "no_of_units": "321",
                "description": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
                "features_amenities": [
                    []
                ],
                "licensed_details": null
            },
            "model_house": [],
            "gallery": [
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/unnamed.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/Wonderful-Panda-Wallpapers-HD-backgrounds.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2018/11/Panda-Wallpapers-for-PC-Desktop.jpeg"
            ],
            "site_plan": [
                null
            ],
            "vicinity_map": {
                "lat": null,
                "long": null
            }
        }
    ],
    "message": "Successfully found all data",
    "status": "200"
}
```

---

##### Get Unit
GET `https://apc.betaprojex.com/app/api/properties/{property_id}/{unit_order_no}`
> unit_order_no = Model Unit order in display starting from 0
##### Response
```json
200 OK
{
    "data": {
        "name": "Duplex (without garage)",
        "featured_image": "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
        "floor_area": "44.5",
        "bedroom": "2",
        "bathroom": "1",
        "parking_space": "0",
        "sample_photos": [
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483.png"
        ],
        "house_specifications": [
            "Long Span Colored Roof",
            "Steel Roof Framings",
            "Tiled Bathroom",
            "Steel Casement Windows",
            "Complete Toilet & Bath",
            "Complete Electrical Wirings and Fixtures",
            "Complete Water/Plumbing Pipes & Fixtures"
        ],
        "floor_plan": [
            {
                "image": "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
                "image_caption": "Ground Floor"
            },
            {
                "image": "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                "image_caption": "Second Floor"
            }
        ]
    },
    "message": "Successfully found all data",
    "status": "200"
}
```

---


##### Get Single Property
GET `https://apc.betaprojex.com/app/api/properties/{property_id}`
##### Response
```json
200 OK
{
    "data": {
        "property_description": {
            "id": "168",
            "logo": "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483.png",
            "property_name": "Paragon Village",
            "location": "Cavite",
            "address": "<p>Brgy. San Agustin / Brgy. Cabuco, Trece Martires, Cavite</p>\n",
            "featured_photos": [
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
                "https://apc.betaprojex.com/wp-content/uploads/2019/01/home-bg001-1128x452.png"
            ],
            "total_area": "23.848",
            "no_of_units": "3,196",
            "description": "EXCEPTIONAL LIFE\nTHROUGH SIMPLE LIVING\nWe often times aspire for excellence in all we do. But excellence can be felt even if done in a simple and mild setting. Living may not be extravagant to be exceptional. In the simplest of things, excellence can be found. Experience this now at Paragon Village.\nWith homes depicting simplicity and comfort, you and your family will surely feel that homey atmosphere, perfect in nurturing your family’s well being. Now, that’s a new take in simple living. Truly, at Paragon Village, life can simply be exceptional.",
            "features_amenities": [
                "Entrance Gate with Guardhouse",
                "Multi-Purpose Hall",
                "Playground",
                "Basketball Court",
                "Centralized Water Supply",
                "Concrete Roads, Curbs and Gutters",
                "Underground Drainage System"
            ],
            "licensed_details": "<p>HLURB LS NO. 032135<br />\nLAND DEVT: DECEMBER 31, 2018<br />\nMAXIMUM SELLING PRICE: P1,700,000.00 (H/L)<br />\nBP 220 | HLURB ADVERTISEMENT APPROVAL NO. AA-STR-071818-0234</p>\n"
        },
        "model_house": [
            {
                "name": "Townhouse",
                "featured_image": false,
                "floor_area": "44",
                "bedroom": "2",
                "bathroom": "1",
                "parking_space": "0"
            },
            {
                "name": "Duplex (without garage)",
                "featured_image": "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
                "floor_area": "44.5",
                "bedroom": "2",
                "bathroom": "1",
                "parking_space": "0"
            }
        ],
        "gallery": [
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg",
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483-1.png",
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/home-bg001-1128x452.png"
        ],
        "site_plan": [
            "https://apc.betaprojex.com/wp-content/uploads/2019/01/BBpmVjN.jpg"
        ],
        "vicinity_map": {
            "lat": "14.2829325",
            "long": "120.8499808"
        }
    },
    "message": "Successfully found all data",
    "status": "200"
}
```

---

#### News & Updates

---

##### Get All News & Updates
GET `https://apc.betaprojex.com/app/api/news`
##### Response
```json
200 OK
{
    "data": [
        {
            "ID": 141,
            "title": "Tripping Schedules",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": false
        },
        {
            "ID": 140,
            "title": "Special Announcements",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": false
        },
        {
            "ID": 139,
            "title": "Seminars",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": "https://apc.betaprojex.comhomes/wp-content/uploads/2018/11/IMG_5191.jpg"
        },
        {
            "ID": 138,
            "title": "Other Activities",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": false
        },
        {
            "ID": 137,
            "title": "Open House",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": false
        },
        {
            "ID": 136,
            "title": "News/Updates",
            "content": "Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum.",
            "thumbnail": "https://apc.betaprojex.comhomes/wp-content/uploads/2018/11/unnamed.jpg"
        }
    ],
    "message": "Successfully found all data",
    "status": "200"
}
```

---

#### Notifications

---

##### Get All Notifications
GET `https://apc.betaprojex.com/app/api/notifications/{user_id}`
##### Response
```json
200 OK
{
    "data": [
        {
            "ID": 166,
            "title": "Be at the Heart of your Dreams!",
            "content": "Mauris rutrum porttitor viverra. Phasellus ac mauris cursus, placerat nulla non, congue orci. Nullam ligula ante, fermentum in hendrerit at, semper a odio. Etiam purus sapien, vehicula ut erat tristique, pellentesque euismod lacus. Morbi ac faucibus elit, eu facilisis libero. Integer gravida bibendum pulvinar. Mauris et purus urna. Cras pharetra ultrices est non accumsan. Proin elit nibh, volutpat blandit dui id, egestas suscipit nibh.\r\n\r\nDonec lacus dui, suscipit quis risus placerat, imperdiet ullamcorper mi. Nullam at purus ac lectus fermentum aliquet. Donec laoreet lacus ipsum, in consequat arcu molestie vitae. Lorem ipsum dolor sit amet, consectetur adipiscing elit. Sed a dui leo. Nunc non augue a sapien pellentesque viverra. Vivamus quis posuere turpis, eu pellentesque velit. Nullam imperdiet urna enim, nec tempus est tincidunt a. Suspendisse orci erat, dapibus ac nisl a, rhoncus ultrices ex. Vestibulum dignissim vehicula eleifend. Quisque consequat eget augue sed hendrerit. Pellentesque iaculis ante quis ultricies facilisis.",
            "thumbnail": "https://apc.betaprojex.com/wp-content/uploads/2019/01/electronic_mark_0_1470133483.png",
            "is_read": "1"
        },
        {
            "ID": 165,
            "title": "Looking for Contractors",
            "content": "Ut fringilla nunc ac nisl suscipit, in ultrices massa tincidunt. Donec in risus at sapien luctus ullamcorper. Aliquam bibendum nunc diam, eu facilisis enim congue quis. Aliquam mauris tellus, sodales ut ipsum eget, interdum venenatis nunc. Etiam finibus fermentum ipsum nec feugiat. Phasellus posuere ipsum ultrices mi commodo, et ornare est semper. Quisque ut dolor ac lacus imperdiet finibus sit amet eget nunc. Donec lacinia purus et lacus luctus, non tristique magna pulvinar.\r\n\r\nVestibulum mi erat, cursus ac tellus ac, viverra iaculis eros. Vivamus ullamcorper semper nisl nec feugiat. Vivamus ornare nisl at efficitur euismod. Sed faucibus justo bibendum fringilla malesuada. Mauris mattis libero a rhoncus consectetur. Aliquam malesuada pulvinar enim, iaculis laoreet justo semper a. Donec mattis varius ullamcorper. Etiam egestas libero magna, non ultrices purus venenatis sit amet. Duis et tincidunt mauris. Phasellus nec rutrum enim. Vivamus quis quam tincidunt urna cursus tristique. Nulla pellentesque, eros eu posuere pharetra, lacus ex interdum justo, sit amet sodales dolor dui eget orci. In vel risus sed leo bibendum ornare.",
            "thumbnail": false,
            "is_read": null
        },
        {
            "ID": 164,
            "title": "Announcement",
            "content": "Sed odio massa, lobortis et sodales eu, interdum quis ligula. Mauris nec est at mauris rhoncus bibendum. Suspendisse sem ante, pharetra ac tristique vel, condimentum in ipsum. Phasellus eget mauris turpis. Maecenas enim nisi, venenatis nec ultricies ac, feugiat eu felis. Vestibulum quis pulvinar ligula, id mollis lacus. Quisque vel lorem leo. Nam non sapien porttitor, porta est a, sollicitudin dolor. Nullam a pellentesque odio.\r\n\r\nNulla eget nulla porttitor, dignissim ipsum sed, blandit justo. Pellentesque a enim dignissim, lacinia tortor in, pellentesque sapien. Duis in tincidunt nulla, sit amet posuere nibh. Curabitur tempor, enim vitae luctus volutpat, dui nisi scelerisque lorem, nec dictum nibh sapien id massa. Nullam ante augue, sodales et sem dignissim, aliquet vestibulum massa. Quisque justo dolor, iaculis ut tempus ac, fringilla non nulla. Integer mattis vestibulum laoreet.",
            "thumbnail": false,
            "is_read": null
        }
    ],
    "message": "Successfully found all data",
    "status": "200"
}
```

---
##### Read a Notification
GET `https://apc.betaprojex.com/app/api/notifications/read/{post_id}/{user_id}`
##### Response
```json
200 OK
{
    "data": {
        "is_success": true
    },
    "message": "Successfully found all data",
    "status": "200"
}
```

---

#### Loan Calculator

---

##### Get Loan Calculator Result
POST `https://apc.betaprojex.com/app/api/calculator/calculate`

**Parameters**


| Name | Type | Description | Sample Data |
| ------ | ------ | ----------- | ----------- |
| tcp    | float | Total Contract Price | 1000000.00 |
| rsv_amount    | float | Reservation Amount | 10000.00 |

##### Response

```json
200 OK
{
    "data": {
        "pagibig": {
            "downpayment": {
                "rate": 10,
                "value": "Php 99,000.00"
            },
            "loan_amount": {
                "rate": 90,
                "value": "Php 891,000.00"
            },
            "monthly_equity": "Php 5,500.00",
            "yearly_amo": {
                "5_years_monthly_amo": "Php 17,433.44",
                "10_years_monthly_amo": "Php 10,117.12",
                "15_years_monthly_amo": "Php 7,761.57",
                "20_years_monthly_amo": "Php 6,643.06",
                "25_years_monthly_amo": "Php 6,016.10",
                "30_years_monthly_amo": "Php 5,631.73"
            }
        },
        "inhouse": {
            "downpayment": {
                "rate": 30,
                "value": "Php 297,000.00"
            },
            "loan_amount": {
                "rate": 70,
                "value": "Php 693,000.00"
            },
            "monthly_equity": "Php 24,750.00",
            "yearly_amo": {
                "5_years_monthly_amo": "Php 15,415.09",
                "10_years_monthly_amo": "Php 12,044.34"
            }
        },
        "bank": {
            "downpayment": {
                "rate": 20,
                "value": "Php 198,000.00"
            },
            "loan_amount": {
                "rate": 80,
                "value": "Php 792,000.00"
            },
            "monthly_equity": "Php 11,000.00",
            "yearly_amo": {
                "5_years_monthly_amo": "Php 15,496.39",
                "10_years_monthly_amo": "Php 8,993.00",
                "15_years_monthly_amo": "Php 6,899.17",
                "20_years_monthly_amo": "Php 5,904.94",
                "25_years_monthly_amo": "Php 5,347.64",
                "30_years_monthly_amo": "Php 5,005.98"
            }
        },
        "deferred": {
            "downpayment": {
                "rate": 0,
                "value": "Php 990,000.00"
            },
            "monthly_equity": "Php 41,250.00"
        },
        "spotCash": {
            "thirty_days": "Php 970,200.00",
            "sixty_days": "Php 980,100.00"
        }
    },
    "message": "Successfully found all data",
    "status": "200"
}
```

#### Office Addresses

---

##### Get All Office Addresses
GET `https://apc.betaprojex.com/app/api/contact`
##### Response
```json
200 OK
{
    "data": [
        {
            "ID": 144,
            "title": "CENTROMALL, CABUYAO OFFICE",
            "location": "2F Brgy. Pulo, Cabuyao, Laguna",
            "office_name": "CENTROMALL OFFICE",
            "complete_location": "2F Centromall Cabuyao, Brgy. Pulo, Cabuyao, Laguna",
            "featured_photos": [
                "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
            ],
            "schedule": [
                {
                    "day": "Monday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Tuesday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Wednesday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Thursday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Friday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Saturday",
                    "time": "8:30AM - 5:30PM"
                },
                {
                    "day": "Sunday",
                    "time": "9:00AM - 4:00PM"
                }
            ],
            "cutoff": "Monday To Satuday Cut - Off : 4:30pm | Sunday Cut - off : 3:00pm",
            "contact_number": "",
            "map_location": {
                "longitude": "121.1289758",
                "latitude": "14.2424298"
            },
            "grab_link": "",
            "waze_link": "https://www.waze.com/livemap?ll=14.2424298,121.1289758&z=10&navigate=yes",
            "googlemap_link": "https://goo.gl/maps/kXYXSPmAYz72"
        },
        {
            "ID": 145,
            "title": "EDSA, QUEZON CITY OFFICE",
            "location": "",
            "office_name": "",
            "complete_location": "",
            "featured_photos": [
                "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
            ],
            "schedule": "",
            "cutoff": "",
            "contact_number": "",
            "map_location": "",
            "grab_link": "",
            "waze_link": "",
            "googlemap_link": ""
        },
        {
            "ID": 146,
            "title": "LIPA, BATANGAS OFFICE",
            "location": "",
            "office_name": "",
            "complete_location": "",
            "featured_photos": [
                "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
            ],
            "schedule": "",
            "cutoff": "",
            "contact_number": "",
            "map_location": "",
            "grab_link": "",
            "waze_link": "",
            "googlemap_link": ""
        },
        {
            "ID": 147,
            "title": "TARLAC CITY OFFICE",
            "location": "2F Brgy. Pulo, Cabuyao, Laguna",
            "office_name": "",
            "complete_location": "",
            "featured_photos": [
                "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
            ],
            "schedule": "",
            "cutoff": "",
            "contact_number": "",
            "map_location": "",
            "grab_link": "",
            "waze_link": "",
            "googlemap_link": ""
        }
    ],
    "message": "Successfully found all data",
    "status": "200"
}
```

---

##### Get Single Office Addresses
GET `https://apc.betaprojex.com/app/api/contact/{office_id}`
##### Response
```json
200 OK
{
    "data": {
        "ID": "144",
        "title": "CENTROMALL, CABUYAO OFFICE",
        "location": "2F Brgy. Pulo, Cabuyao, Laguna",
        "office_name": "CENTROMALL OFFICE",
        "complete_location": "2F Centromall Cabuyao, Brgy. Pulo, Cabuyao, Laguna",
        "featured_photos": [
            "https://apc.betaprojex.com/app/assets/images/default-thumbnail.jpg"
        ],
        "schedule": [
            {
                "day": "Monday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Tuesday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Wednesday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Thursday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Friday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Saturday",
                "time": "8:30AM - 5:30PM"
            },
            {
                "day": "Sunday",
                "time": "9:00AM - 4:00PM"
            }
        ],
        "cutoff": "Monday To Satuday Cut - Off : 4:30pm | Sunday Cut - off : 3:00pm",
        "contact_number": "",
        "map_location": {
            "longitude": "121.1289758",
            "latitude": "14.2424298"
        },
        "grab_link": "",
        "waze_link": "https://www.waze.com/livemap?ll=14.2424298,121.1289758&z=10&navigate=yes",
        "googlemap_link": "https://goo.gl/maps/kXYXSPmAYz72"
    },
    "message": "Successfully found all data",
    "status": "200"
}
```

---
