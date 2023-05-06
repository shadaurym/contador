<template>
  <div>
    <h2>chofer llego a recojer</h2>
    <p>{{info.loadNumber}}</p>
    <span v-for="orden in info.Orders" :key="orden">No de orden: {{orden.order_num}}</span>
    <p v-for="chofer in info.Vehicles" :key="chofer">chofer: {{chofer.driver}}</p>
    <span v-for="modelo in info.Vehicles" :key="modelo">vehiculo: ford{{modelo.model}} , placa: {{modelo.policy_no}}</span>
    
  </div>
</template>

<script>
export default {
   data() {
    return {
        info: {
    "_id": "644ebfcbe9216d3cb5256171",
    "slot_id": {
        "_id": "644ebfc3e9216d3cb525616b",
        "updated_by": null,
        "created_by": null,
        "createdAt": "2023-04-30T19:21:39.877Z",
        "description": null,
        "date": "2023-04-30T00:00:00.000Z",
        "warehouse": "5e184b8ac86dd63a98d322da",
        "end_time": "15:45",
        "start_time": "15:25",
        "name": null,
        "__v": 0
    },
    "bay_id": {
        "_id": "644ebfc3e9216d3cb525616c",
        "__v": 0,
        "timeSlot": "644ebfc3e9216d3cb525616b",
        "updated_by": null,
        "created_by": null,
        "createdAt": "2023-04-30T19:21:39.879Z",
        "description": null,
        "transporterCost": null,
        "bayIndex": null,
        "name": "Bay 1"
    },
    "bayIndex": null,
    "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
    "dateTime": {
        "slotTime": {
            "end": "15:45",
            "start": "15:25"
        },
        "date": "04/30/2023"
    },
    "rejectedVehicles": [],
    "damagedProducts": [],
    "logbooks": [],
    "exceptions": {
        "boxesScannedTwice": [],
        "wrongBoxNotUnloaded": [],
        "wrongBoxScanned": [],
        "boxesUnloaded": [],
        "other": []
    },
    "resetLog": [
        {
            "remark": "data.remark",
            "timeStamp": "2023-04-30T20:10:03.981Z",
            "userEmail": "admin@flai.com.do",
            "_id": "644ecb1be071403f2c5bb39e"
        },
        {
            "remark": "data.remark",
            "timeStamp": "2023-05-01T16:40:31.934Z",
            "userEmail": "admin@flai.com.do",
            "_id": "644feb7ff2eb5b698a6665e9"
        },
        {
            "remark": "data.remark",
            "timeStamp": "2023-05-01T16:53:18.782Z",
            "userEmail": "admin@flai.com.do",
            "_id": "644fee7e376c6b69f9978daa"
        }
    ],
    "loadHistory": [],
    "customerLoadCertification": {
        "clcTimeStamp": null,
        "info": "",
        "file": null,
        "status": "Pending"
    },
    "transporterLoadCertification": {
        "tlcTimeStamp": null,
        "info": "",
        "file": null,
        "status": "Pending"
    },
    "startLocation": {
        "lng": null,
        "lat": null
    },
    "dsipatchRequestSent": false,
    "driverStatus": {
        "arrival": "2023-05-01T16:54:15.751Z"
    },
    "loadProperties": {
        "numberOfBoxs": null,
        "numberOfOrders": null,
        "weight": null,
        "volume": null
    },
    "loadingStatus": {
        "slotEndTime": "2023-04-30T19:45:00.000Z",
        "slotStartTime": "2023-04-30T19:25:00.000Z",
        "deliveryETA": "2023-04-30T19:55:00.000Z",
        "deniedApproval": "2023-05-01T16:53:18.782Z",
        "expectingApproval": "2023-05-01T16:53:27.935Z",
        "dispatchApprovalTimeStamp": null,
        "deliverTimeStamp": null,
        "loadedTimeStamp": null,
        "loadingTimeStamp": null,
        "approvedTimeStamp": "2023-05-01T16:54:10.803Z",
        "recieveInAccouningTimeStamp": null,
        "reopenCLCTimeStamp": null,
        "approveCLCTimeStamp": null,
        "uploadCLCTimeStamp": null,
        "reopenTLCTimeStamp": null,
        "approveTLCTimeStamp": null,
        "uploadTLCTimeStamp": null,
        "fractionNumber": "2/2",
        "text": "Driver Arrival",
        "volumeLoaded": 0,
        "loadVolume": 0.136,
        "numberOfOrders": 2,
        "numberOfBoxes": 2,
        "loadWeight": 340,
        "boxesLoaded": 0,
        "orderLoadPercentage": 2,
        "volumeLoadedPercent": 0,
        "voluemWaitingToBeLoaded": 2
    },
    "updated_by": null,
    "created_by": null,
    "createdAt": "2023-04-30T19:21:47.726Z",
    "customer_id": null,
    "warehouse": "5e184b8ac86dd63a98d322da",
    "transportCost": 97.43,
    "loadCost": 100,
    "profitability": 2.569999999999993,
    "Button4_Status": null,
    "Button3_Status": null,
    "Button2_Status": null,
    "Button1_Status": null,
    "shipper": [
        {
            "_id": "61a8e1d04395b54b0da5aa96",
            "serviceType": "FTL",
            "name": "Javilla Testing"
        }
    ],
    "loadApproved": false,
    "vehicleType": "5ea07fd738811734c11bb0e9",
    "allowOrderChangesAtDelivery": false,
    "scanningRequired": false,
    "loadForeignkeys": {
        "returnTransportCostForLoad": null,
        "transporterCostId": "61a8e5634395b54b0da5aad5",
        "locationId": "644feeb2376c6b69f9978db1",
        "transporterId": "61a8e2c84395b54b0da5aa9d",
        "vehicleId": "62387ea85a2e724354978a3d"
    },
    "date": "2023-04-30T00:00:00.000Z",
    "__v": 4,
    "loadType": "B2B Delivery",
    "currencyExchange": {
        "atTheTimeOfAssigning": 55.6,
        "dateAtTheTimeOfAssigning": "2023-05-01T16:53:27.861Z"
    },
    "reqBodyCacheForSelectingDriver": {
        "loadMapId": "644ebfcbe9216d3cb5256171",
        "transporterSelection": false,
        "date": "04/30/2023",
        "loadingStartTime": "2023-04-30T19:25:00.000Z",
        "shipperServices": [
            {
                "_id": "61a8e1d04395b54b0da5aa96",
                "name": "Javilla Testing",
                "serviceType": "FTL"
            }
        ],
        "loadType": "B2B Delivery",
        "scanningRequired": false,
        "allowOrderChangesAtDelivery": false,
        "aditionalCharacterstic": "",
        "deliveryETA": "2023-04-30T19:55:00.000Z",
        "transporterService": "FTL",
        "optimizeBy": "route",
        "providerZoneGroup": {
            "_id": "5ebfe99b40e2d62001cba3ab",
            "name": "Provider's Zone Group"
        }
    },
    "serviceType": null,
    "plannedProfitability": {
        "profitability": {
            "transportCost": 97.43,
            "revenue": 100,
            "profitability": 2.569999999999993
        },
        "allVariable": {
            "loadDetails": {
                "_id": "644ebfcbe9216d3cb5256171",
                "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                "bayName": "Bay 1",
                "slotTime": "15:25-15:45",
                "warehouse": "AJFA-Test",
                "exchangeRateAtTheTimeOfAssigning": 55.6
            },
            "loadVariable": {
                "return": false,
                "nonReturn": true,
                "returnWA": false,
                "comment": "weight is in kgs, volume is in M3, distance in meters, currency in USD$. ",
                "shippers": [],
                "loadVariables": {
                    "rejectedVehicles": [],
                    "comment": "loadLevel these are the counters for entire load",
                    "loadLevel": {
                        "return": false,
                        "returnWAVolume": 0,
                        "returnWAWeight": 0,
                        "returnWADeliveryPoint": 0,
                        "returnWAOrder": 0,
                        "returnWABoxes": 0,
                        "loadUnloadingTime": 0,
                        "loadLoadingTime": 0,
                        "actualDistance": 0,
                        "plannedDistance": 43.43,
                        "returnVolume": 0,
                        "returnWeight": 0,
                        "deliveryPointReturn": 0,
                        "returnOrder": 0,
                        "returnBoxes": 0,
                        "notReturnVolume": 0.136,
                        "notReturnWeight": 340,
                        "deliveryPointNonReturn": 1,
                        "notReturnOrder": 2,
                        "notReturnBoxes": 17,
                        "providerZone": [
                            "5eda5261cb707d20b6d16d59",
                            "5eda5261cb707d20b6d16d58"
                        ],
                        "returnSpecialHandlingProduct": [],
                        "nonReturnSpecialHandlingProduct": [],
                        "returnWASpecialHandlingProduct": [],
                        "returnDeliveryCycleOfOrders": [],
                        "nonReturnDeliveryCycleOfOrders": [],
                        "returnWADeliveryCycleOfOrders": [],
                        "anchorProviderZone": {
                            "_id": "5eda5261cb707d20b6d16d58",
                            "name": "Santo Domingo Este",
                            "labelCoordinate": {
                                "coordinates": [
                                    -69.74519937558594,
                                    18.545341170012993
                                ],
                                "type": "Point"
                            }
                        },
                        "sumOfDistances": 47.43,
                        "nonReturn": true,
                        "orderRouteOrder": [
                            0,
                            1
                        ],
                        "cost": {
                            "1100231051": {
                                "deliveryPoints": 5,
                                "distance": 11.830394265232975
                            },
                            "1100231104": {
                                "deliveryPoints": 5,
                                "distance": 31.599605734767025
                            }
                        }
                    },
                    "comment2": "orderLevel these are the counters for entire order",
                    "orderLevel": [
                        {
                            "distanceToWarehouse": 12.92,
                            "orderNum": "1100231051",
                            "id": "641238be841713a7f50430d0",
                            "zoneId": "61a8e2584395b54b0da5aa9a",
                            "providerZoneId": "5eda5261cb707d20b6d16d59",
                            "notReturnBoxes": 2,
                            "notReturnWeight": 40,
                            "notReturnVolume": 0.016,
                            "isReturn": false,
                            "returnBoxes": 0,
                            "returnWeight": 0,
                            "returnVolume": 0,
                            "deliveryCycle": null,
                            "deliveryCycleNonReturn": null,
                            "ordersOnSameDeliveryPoint": 2,
                            "cost": {
                                "boxes": 4
                            }
                        },
                        {
                            "distanceToWarehouse": 34.51,
                            "orderNum": "1100231104",
                            "id": "6414cabc1779c41c3823aa87",
                            "zoneId": "61a8e2584395b54b0da5aa9a",
                            "providerZoneId": "5eda5261cb707d20b6d16d58",
                            "notReturnBoxes": 15,
                            "notReturnWeight": 300,
                            "notReturnVolume": 0.12,
                            "isReturn": false,
                            "returnBoxes": 0,
                            "returnWeight": 0,
                            "returnVolume": 0,
                            "deliveryCycle": null,
                            "deliveryCycleNonReturn": null,
                            "ordersOnSameDeliveryPoint": 2,
                            "cost": {
                                "boxes": 30
                            }
                        }
                    ],
                    "comment3": "deliveryPointLevel these are the counters for deliveryPoint",
                    "deliveryPointLevel": [
                        {
                            "orders": [
                                "1100231051",
                                "1100231104"
                            ],
                            "clientId": "31-zone-61a8e2584395b54b0da5aa9a",
                            "returnWAVolume": 0,
                            "returnWAWeight": 0,
                            "returnWAOrder": 0,
                            "returnWABoxes": 0,
                            "returnVolume": 0,
                            "returnWeight": 0,
                            "returnOrder": 0,
                            "returnBoxes": 0,
                            "notReturnVolume": 0.136,
                            "notReturnWeight": 340,
                            "notReturnOrder": 2,
                            "notReturnBoxes": 17,
                            "providerZone": "5eda5261cb707d20b6d16d58",
                            "zoneId": "61a8e2584395b54b0da5aa9a",
                            "cost": {
                                "1100231051": {
                                    "volume": 1.1764705882352942
                                },
                                "1100231104": {
                                    "volume": 8.823529411764705
                                }
                            }
                        }
                    ],
                    "loadVolume": 0.136,
                    "loadWeight": 340,
                    "maxDimension": 0.2,
                    "clients": [
                        "31-zone-61a8e2584395b54b0da5aa9a"
                    ]
                },
                "shipperVariables": [
                    {
                        "name": "Javilla Testing",
                        "return": false,
                        "nonReturn": true,
                        "returnWA": false,
                        "loadLevelComment": "Javilla Testing :  counters for entire load",
                        "loadLevel": {
                            "loadUnloadingTime": 0,
                            "loadLoadingTime": 0,
                            "actualDistance": 0,
                            "plannedDistance": 43.43,
                            "returnWAVolume": 0,
                            "returnWAWeight": 0,
                            "returnWADeliveryPoint": 0,
                            "returnWAOrder": 0,
                            "returnWABoxes": 0,
                            "returnVolume": 0,
                            "returnWeight": 0,
                            "deliveryPointReturn": 0,
                            "returnOrder": 0,
                            "returnBoxes": 0,
                            "notReturnVolume": 0.136,
                            "notReturnWeight": 340,
                            "deliveryPointNonReturn": 1,
                            "notReturnOrder": 2,
                            "notReturnBoxes": 17,
                            "shipperZone": [
                                "61a8e2584395b54b0da5aa9a"
                            ],
                            "sumOfDistances": 47.43,
                            "returnSpecialHandlingProduct": [],
                            "nonReturnSpecialHandlingProduct": [],
                            "returnWASpecialHandlingProduct": [],
                            "returnDeliveryCycleOfOrders": [],
                            "nonReturnDeliveryCycleOfOrders": [],
                            "returnWADeliveryCycleOfOrders": [],
                            "orderRouteOrder": [
                                0,
                                1
                            ],
                            "orderCost": [
                                {
                                    "_id": "641238be841713a7f50430d0",
                                    "name": "1100231051",
                                    "weight": 40,
                                    "volume": 0.016,
                                    "isReturn": false,
                                    "returnWA": false,
                                    "boxes": 2,
                                    "client": "31",
                                    "order_id": {
                                        "_id": "641238be841713a7f50430d0",
                                        "order_num": "1100231051",
                                        "customer": {
                                            "_id": "61a8e1d04395b54b0da5aa96",
                                            "zoneGroup": "61a8e21a4395b54b0da5aa98",
                                            "updated_by": null,
                                            "created_group": "EXO",
                                            "created_by": "admin@flai.com.do",
                                            "createdAt": "2021-12-02T15:10:08.016Z",
                                            "contact_ids": [
                                                null
                                            ],
                                            "email": "mrmiguetara@gmail.com",
                                            "contacts": [
                                                {}
                                            ],
                                            "telephone2": "",
                                            "telephone1": "8094034881",
                                            "website": "http://mrmiguetara.me",
                                            "RNC_no": "12345678946",
                                            "description": "",
                                            "color": "",
                                            "icon": null,
                                            "postal_code": "125050",
                                            "tax_id": "u6777",
                                            "industry": "Retail",
                                            "active": "true",
                                            "address": "45",
                                            "city": "Santo Domingo",
                                            "country": "Dominican Republic",
                                            "rating": null,
                                            "name": "Javilla Testing",
                                            "isDeleted": false,
                                            "__v": 0
                                        },
                                        "rejectedTimestamp": null,
                                        "deliveryTimestamp": null,
                                        "price": null,
                                        "serviceType": "FTL",
                                        "deliveryAttempted": [],
                                        "exceptions": [],
                                        "products": [
                                            {
                                                "exceptionRaised": false,
                                                "product": {
                                                    "_id": "61a8e66d4395b54b0da5ab05",
                                                    "createdAt": "2021-11-30T08:58:01.300Z",
                                                    "createdBy": "mgarrido@flai.com.do",
                                                    "updatedBy": "mgarrido@flai.com.do",
                                                    "isDeleted": false,
                                                    "volume": 8000,
                                                    "height": 20,
                                                    "width": 20,
                                                    "length": 20,
                                                    "weight": 20,
                                                    "unitDetails": {
                                                        "unitWeight": 1,
                                                        "unitVolume": 1,
                                                        "defaultNumberOfUnit": 1
                                                    },
                                                    "qrCode": "G034188",
                                                    "description": "Oro puro del bueno",
                                                    "measurementUnit": "cm",
                                                    "shipper": "61a8e1d04395b54b0da5aa96",
                                                    "productId": "10",
                                                    "__v": 0
                                                },
                                                "name": "10",
                                                "status": null,
                                                "quantity": 2,
                                                "quantityBefore": null,
                                                "overRideTotalUnit": null,
                                                "qrCode": "8",
                                                "defaultQRCode": null,
                                                "loaded": false,
                                                "weight": 40,
                                                "volume": 0.016,
                                                "scaningTimestamp": "2023-03-15T21:29:34.079Z",
                                                "unitWeight": 20,
                                                "unitVolume": 0.008,
                                                "loadingTimestamp": null,
                                                "deliveryTimestamp": null,
                                                "measurementUnit": "cm",
                                                "scanOneByOne": "yes",
                                                "loadScanningCounter": 0,
                                                "description": "Oro puro del bueno",
                                                "contains": null,
                                                "specialHandlingAndBillingType": null,
                                                "damagedChargeCurrency": "USD",
                                                "damagedChargePrice": 0,
                                                "_id": "641238be841713a7f50430d1"
                                            }
                                        ],
                                        "warehouse": "5e184b8ac86dd63a98d322da",
                                        "transporter_id": null,
                                        "finalOrderLocation": {
                                            "lat": null,
                                            "lng": null
                                        },
                                        "addAdditionalInfo": [],
                                        "deliveryImages": null,
                                        "created_group": "EXO",
                                        "type": "loads",
                                        "comment_by": null,
                                        "comment": null,
                                        "islatest": true,
                                        "isactive": true,
                                        "created_by": "admin@flai.com.do",
                                        "createdAt": "2023-03-15T21:29:34.175Z",
                                        "optimizerTimestamp": null,
                                        "perLoadState": [
                                            {
                                                "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                                                "state": "Assigned",
                                                "loadingTimestampStart": null,
                                                "loadingTimestampEnd": null,
                                                "warehouse": "AJFA-Test",
                                                "timeslot": "15:25 - 15:45",
                                                "loadDate": "Sun Apr 30 2023 20:35:30 GMT+0000 (Coordinated Universal Time)",
                                                "bay": "Bay 1",
                                                "assignTimeStamp": "2023-04-30T20:35:30.396Z",
                                                "exceptions": [],
                                                "deliveryAttempted": [],
                                                "serviceType": null,
                                                "price": null,
                                                "deliveryTimestamp": null,
                                                "rejectedTimestamp": null,
                                                "loadDetails": {
                                                    "vehicleNumber": "3",
                                                    "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                                                    "transporterName": "Javilla Transport",
                                                    "vehicleId": "62387ea85a2e724354978a3d",
                                                    "loadId": "644ebfcbe9216d3cb5256171",
                                                    "vehicleType": "5ea07fd738811734c11bb0e9",
                                                    "driverName": "Kenny Martinez"
                                                },
                                                "deliveryImages": null,
                                                "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
                                                "returnServiceOffering": null,
                                                "_id": "644ed1125f5dc8433eb12b13",
                                                "loadId": "644ebfcbe9216d3cb5256171"
                                            }
                                        ],
                                        "status": "Assigned",
                                        "imported_filename": "Orders (1) (61) (1) (54).xlsx",
                                        "providerZone": "5eda5261cb707d20b6d16d59",
                                        "zone": "61a8e2584395b54b0da5aa9a",
                                        "no_of_boxes": 2,
                                        "volume": 0.016,
                                        "authorized_by": "flaiAdmin",
                                        "final_price": null,
                                        "weight": 40,
                                        "pickup_time": null,
                                        "pickup_date": null,
                                        "expected_time": "23:00",
                                        "expected_date": "2023-03-18T23:00:00.000Z",
                                        "cost": 22.01,
                                        "hasAssociatedOrder": false,
                                        "deliveryCycle": null,
                                        "autoCreateReturnOrder": false,
                                        "isReturn": false,
                                        "latitude": "18.5290574",
                                        "longitude": "-69.9107115",
                                        "zipCode": "10111",
                                        "province": "santo domingo",
                                        "city": "distrito nacional",
                                        "sector": "bella vista",
                                        "address": "km. 22, los mina  edif. e9-15. santo domingo este",
                                        "countryCode": null,
                                        "phone": null,
                                        "email": null,
                                        "Official_ID": null,
                                        "client_name": "Wilson",
                                        "client_id": "31",
                                        "__v": 0,
                                        "loadDetails": null,
                                        "returnServiceOffering": null,
                                        "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
                                        "quantityBefore": null
                                    },
                                    "deliveryCycle": null,
                                    "specialHandlingProductsObj": {
                                        "numberOfProducts": 0,
                                        "weight": 0,
                                        "volume": 0
                                    },
                                    "distance": 20020.02
                                },
                                {
                                    "_id": "6414cabc1779c41c3823aa87",
                                    "name": "1100231104",
                                    "weight": 300,
                                    "volume": 0.12,
                                    "isReturn": false,
                                    "returnWA": false,
                                    "boxes": 15,
                                    "client": "31",
                                    "order_id": {
                                        "_id": "6414cabc1779c41c3823aa87",
                                        "order_num": "1100231104",
                                        "customer": {
                                            "_id": "61a8e1d04395b54b0da5aa96",
                                            "zoneGroup": "61a8e21a4395b54b0da5aa98",
                                            "updated_by": null,
                                            "created_group": "EXO",
                                            "created_by": "admin@flai.com.do",
                                            "createdAt": "2021-12-02T15:10:08.016Z",
                                            "contact_ids": [
                                                null
                                            ],
                                            "email": "mrmiguetara@gmail.com",
                                            "contacts": [
                                                {}
                                            ],
                                            "telephone2": "",
                                            "telephone1": "8094034881",
                                            "website": "http://mrmiguetara.me",
                                            "RNC_no": "12345678946",
                                            "description": "",
                                            "color": "",
                                            "icon": null,
                                            "postal_code": "125050",
                                            "tax_id": "u6777",
                                            "industry": "Retail",
                                            "active": "true",
                                            "address": "45",
                                            "city": "Santo Domingo",
                                            "country": "Dominican Republic",
                                            "rating": null,
                                            "name": "Javilla Testing",
                                            "isDeleted": false,
                                            "__v": 0
                                        },
                                        "rejectedTimestamp": null,
                                        "deliveryTimestamp": "2023-03-30T13:27:26.295Z",
                                        "price": null,
                                        "serviceType": "FTL",
                                        "deliveryAttempted": [],
                                        "exceptions": [],
                                        "products": [
                                            {
                                                "exceptionRaised": false,
                                                "product": {
                                                    "_id": "61a8e66d4395b54b0da5ab05",
                                                    "createdAt": "2021-11-30T08:58:01.300Z",
                                                    "createdBy": "mgarrido@flai.com.do",
                                                    "updatedBy": "mgarrido@flai.com.do",
                                                    "isDeleted": false,
                                                    "volume": 8000,
                                                    "height": 20,
                                                    "width": 20,
                                                    "length": 20,
                                                    "weight": 20,
                                                    "unitDetails": {
                                                        "unitWeight": 1,
                                                        "unitVolume": 1,
                                                        "defaultNumberOfUnit": 1
                                                    },
                                                    "qrCode": "G034188",
                                                    "description": "Oro puro del bueno",
                                                    "measurementUnit": "cm",
                                                    "shipper": "61a8e1d04395b54b0da5aa96",
                                                    "productId": "10",
                                                    "__v": 0
                                                },
                                                "name": "10",
                                                "status": "",
                                                "quantity": 15,
                                                "quantityBefore": null,
                                                "overRideTotalUnit": null,
                                                "qrCode": "3",
                                                "defaultQRCode": null,
                                                "loaded": false,
                                                "weight": 300,
                                                "volume": 0.12,
                                                "scaningTimestamp": "2023-03-17T20:17:00.522Z",
                                                "unitWeight": 20,
                                                "unitVolume": 0.008,
                                                "loadingTimestamp": null,
                                                "deliveryTimestamp": "2023-03-30T13:27:17.430Z",
                                                "measurementUnit": "cm",
                                                "scanOneByOne": "no",
                                                "loadScanningCounter": 0,
                                                "description": "Oro puro del bueno",
                                                "contains": null,
                                                "specialHandlingAndBillingType": null,
                                                "damagedChargeCurrency": "USD",
                                                "damagedChargePrice": 0,
                                                "_id": "64184ca91779c41c3823aab0"
                                            }
                                        ],
                                        "warehouse": "5e184b8ac86dd63a98d322da",
                                        "transporter_id": null,
                                        "finalOrderLocation": {
                                            "lat": 18.5304427,
                                            "lng": -69.8041564
                                        },
                                        "addAdditionalInfo": [],
                                        "deliveryImages": null,
                                        "created_group": "EXO",
                                        "type": "loads",
                                        "comment_by": null,
                                        "comment": null,
                                        "islatest": true,
                                        "isactive": true,
                                        "created_by": "admin@flai.com.do",
                                        "createdAt": "2023-03-17T20:17:00.571Z",
                                        "optimizerTimestamp": null,
                                        "perLoadState": [
                                            {
                                                "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                                                "state": "Assigned",
                                                "loadingTimestampStart": null,
                                                "loadingTimestampEnd": null,
                                                "warehouse": "AJFA-Test",
                                                "timeslot": "15:25 - 15:45",
                                                "loadDate": "Sun Apr 30 2023 20:35:27 GMT+0000 (Coordinated Universal Time)",
                                                "bay": "Bay 1",
                                                "assignTimeStamp": "2023-04-30T20:35:27.918Z",
                                                "exceptions": [],
                                                "deliveryAttempted": [],
                                                "serviceType": null,
                                                "price": null,
                                                "deliveryTimestamp": null,
                                                "rejectedTimestamp": null,
                                                "loadDetails": {
                                                    "vehicleNumber": "3",
                                                    "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                                                    "transporterName": "Javilla Transport",
                                                    "vehicleId": "62387ea85a2e724354978a3d",
                                                    "loadId": "644ebfcbe9216d3cb5256171",
                                                    "vehicleType": "5ea07fd738811734c11bb0e9",
                                                    "driverName": "Kenny Martinez"
                                                },
                                                "deliveryImages": null,
                                                "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
                                                "returnServiceOffering": null,
                                                "_id": "644ed10f5f5dc8433eb12b0e",
                                                "loadId": "644ebfcbe9216d3cb5256171"
                                            }
                                        ],
                                        "status": "Assigned",
                                        "imported_filename": "Orders (1) (61) (1) (57).xlsx",
                                        "providerZone": "5eda5261cb707d20b6d16d58",
                                        "zone": "61a8e2584395b54b0da5aa9a",
                                        "no_of_boxes": 15,
                                        "volume": 0.12,
                                        "authorized_by": "flaiAdmin",
                                        "final_price": null,
                                        "weight": 300,
                                        "pickup_time": "NaN:NaN",
                                        "pickup_date": null,
                                        "expected_time": "23:0",
                                        "expected_date": "2023-03-20T23:00:00.000Z",
                                        "cost": 75.42,
                                        "hasAssociatedOrder": false,
                                        "deliveryCycle": null,
                                        "autoCreateReturnOrder": false,
                                        "isReturn": false,
                                        "latitude": "18.5126035",
                                        "longitude": "-69.8001645",
                                        "zipCode": "10111",
                                        "province": "santo domingo",
                                        "city": "distrito nacional",
                                        "sector": "bella vista",
                                        "address": "km. 22, los mina  edif. e9-15. santo domingo este",
                                        "countryCode": "1",
                                        "phone": "8299808621",
                                        "email": "km@gm.com",
                                        "Official_ID": null,
                                        "client_name": "Wilson",
                                        "client_id": "31",
                                        "__v": 0,
                                        "orderSequence": null,
                                        "loadDetails": null,
                                        "returnServiceOffering": null,
                                        "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
                                        "quantityBefore": null
                                    },
                                    "deliveryCycle": null,
                                    "specialHandlingProductsObj": {
                                        "numberOfProducts": 0,
                                        "weight": 0,
                                        "volume": 0
                                    }
                                }
                            ],
                            "ratio": 1,
                            "selectedZone": {
                                "_id": "61a8e2584395b54b0da5aa9a",
                                "name": "Capital",
                                "labelCoordinate": {
                                    "type": "Point",
                                    "coordinates": [
                                        -69.84906990376727,
                                        18.507346368436835
                                    ]
                                }
                            },
                            "pricing": {
                                "1100231051": {
                                    "boxes": 11.76470588235294
                                },
                                "1100231104": {
                                    "boxes": 88.23529411764706
                                }
                            }
                        },
                        "orderLevelComment": "Javilla Testing : counters for entire order",
                        "orderLevel": [
                            {
                                "isReturnWA": false,
                                "orderNum": "1100231051",
                                "id": "641238be841713a7f50430d0",
                                "zoneId": "61a8e2584395b54b0da5aa9a",
                                "notReturnBoxes": 2,
                                "notReturnWeight": 40,
                                "notReturnVolume": 0.016,
                                "returnBoxes": 0,
                                "returnWeight": 0,
                                "returnVolume": 0,
                                "deliveryCycle": null,
                                "deliveryCycleNonReturn": null,
                                "isReturn": false,
                                "distanceToWarehouse": 12.92,
                                "ordersOnSameDeliveryPoint": 2,
                                "pricing": {}
                            },
                            {
                                "isReturnWA": false,
                                "orderNum": "1100231104",
                                "id": "6414cabc1779c41c3823aa87",
                                "zoneId": "61a8e2584395b54b0da5aa9a",
                                "notReturnBoxes": 15,
                                "notReturnWeight": 300,
                                "notReturnVolume": 0.12,
                                "returnBoxes": 0,
                                "returnWeight": 0,
                                "returnVolume": 0,
                                "deliveryCycle": null,
                                "deliveryCycleNonReturn": null,
                                "isReturn": false,
                                "distanceToWarehouse": 34.51,
                                "ordersOnSameDeliveryPoint": 2,
                                "pricing": {}
                            }
                        ],
                        "deliveryPointLevelComment": "Javilla Testing: counters for deliveryPoint",
                        "deliveryPointLevel": [
                            {
                                "clientId": "31-zone-61a8e2584395b54b0da5aa9a",
                                "returnWAVolume": 0,
                                "returnWAWeight": 0,
                                "returnWAOrder": 0,
                                "returnWABoxes": 0,
                                "returnVolume": 0,
                                "returnWeight": 0,
                                "returnOrder": 0,
                                "returnBoxes": 0,
                                "notReturnVolume": 0.136,
                                "notReturnWeight": 340,
                                "notReturnOrder": 2,
                                "notReturnBoxes": 17,
                                "orders": [
                                    "1100231051",
                                    "1100231104"
                                ],
                                "shipperZone": "61a8e2584395b54b0da5aa9a"
                            }
                        ],
                        "id": "61a8e1d04395b54b0da5aa96"
                    }
                ]
            },
            "vehicleVariable": [
                {
                    "vehicleTypeId": "5ea07fd738811734c11bb0e9",
                    "vehicleTypeName": "1.3T 9.53M3",
                    "transporters": [
                        {
                            "transporter": "Javilla Transport",
                            "id": "61a8e2c84395b54b0da5aa9d"
                        }
                    ]
                }
            ],
            "revenueMatrix": [
                {
                    "name": "Javilla Transport",
                    "id": "61a8e2c84395b54b0da5aa9d",
                    "totalRevenue": 100,
                    "details": [
                        {
                            "totalAmount": 100,
                            "name": "Javilla Testing",
                            "id": "61a8e1d04395b54b0da5aa96",
                            "offeringId": "61a8e4dd4395b54b0da5aaa5",
                            "offeringName": "12",
                            "serviceType": {
                                "orders": "Total Per Load",
                                "boxes": "Total Per Load",
                                "deliveryPoints": "Total Per Load",
                                "weight": "Total Per Load",
                                "volume": "Total Per Load",
                                "distance": "Total Per Load",
                                "loading": "Total Per Load",
                                "unloading": "Total Per Load",
                                "deliveryCycle": "Total Per Order",
                                "specialBilling": "Per Product Volume"
                            },
                            "nonReturnPrice": 100,
                            "vehicleType": "1.3T 9.53M3",
                            "vehicleTypeId": "5ea07fd738811734c11bb0e9",
                            "chargesDetails": {
                                "orders": [],
                                "boxes": [
                                    {
                                        "type": "fixed",
                                        "rangeStart": 1,
                                        "rangeEnd": 30,
                                        "price": 100,
                                        "_id": "62703060151afbbbc75282fc"
                                    },
                                    {
                                        "type": "fixed",
                                        "rangeStart": 31,
                                        "rangeEnd": 500,
                                        "price": 30,
                                        "_id": "62703060151afbbbc75282fb"
                                    }
                                ],
                                "deliveryPoints": [],
                                "weight": [],
                                "volume": [],
                                "distance": [],
                                "loading": [],
                                "unloading": [],
                                "deliveryCycle": [],
                                "specialBilling": [],
                                "currency": "USD $"
                            },
                            "nonReturnChargesDetails": {
                                "orders": [],
                                "boxes": [
                                    {
                                        "type": "fixed",
                                        "rangeStart": 1,
                                        "rangeEnd": 30,
                                        "price": 100,
                                        "_id": "62703060151afbbbc75282fc"
                                    },
                                    {
                                        "type": "fixed",
                                        "rangeStart": 31,
                                        "rangeEnd": 500,
                                        "price": 30,
                                        "_id": "62703060151afbbbc75282fb"
                                    }
                                ],
                                "deliveryPoints": [],
                                "weight": [],
                                "volume": [],
                                "distance": [],
                                "loading": [],
                                "unloading": [],
                                "deliveryCycle": [],
                                "specialBilling": [],
                                "currency": "USD $"
                            },
                            "nonReturnParamsDetails": {
                                "orders": 0,
                                "boxes": 100,
                                "deliveryPoints": 0,
                                "weight": 0,
                                "volume": 0,
                                "distance": 0,
                                "loading": 0,
                                "unloading": 0,
                                "deliveryCycle": 0,
                                "specialBilling": 0
                            }
                        }
                    ],
                    "loadLevelDetails": {
                        "1100231051": {
                            "boxes": 11.76470588235294
                        },
                        "1100231104": {
                            "boxes": 88.23529411764706
                        }
                    },
                    "orderLevelDetails": {
                        "1100231051": {},
                        "1100231104": {}
                    },
                    "deliveryPointLevelDetails": []
                }
            ],
            "costMatrix": [
                {
                    "transporterName": "Javilla Transport",
                    "transporterId": "61a8e2c84395b54b0da5aa9d",
                    "vehiclePricing": [
                        {
                            "truckType": "1.3T 9.53M3",
                            "truckTypeId": "5ea07fd738811734c11bb0e9",
                            "cost": 97.43,
                            "nonReturnOfferingName": "1",
                            "nonReturnOfferingId": "61a8e5634395b54b0da5aad5",
                            "nonReturnChargesDetails": {
                                "orders": [],
                                "boxes": [
                                    {
                                        "type": "incremental",
                                        "rangeStart": 1,
                                        "rangeEnd": 9999,
                                        "price": 2,
                                        "_id": "62cc4de85b7dcfc692a2111f"
                                    }
                                ],
                                "deliveryPoints": [
                                    {
                                        "type": "fixed",
                                        "rangeStart": 1,
                                        "rangeEnd": 9999,
                                        "price": 10,
                                        "_id": "62cc4de85b7dcfc692a2111e"
                                    }
                                ],
                                "weight": [],
                                "volume": [
                                    {
                                        "type": "fixed",
                                        "rangeStart": 1,
                                        "rangeEnd": 9999,
                                        "price": 10,
                                        "_id": "62cc4de85b7dcfc692a2111d"
                                    }
                                ],
                                "distance": [
                                    {
                                        "type": "incremental",
                                        "rangeStart": 1,
                                        "rangeEnd": 9999,
                                        "price": 1,
                                        "_id": "62cc4de85b7dcfc692a2111c"
                                    }
                                ],
                                "loading": [],
                                "unloading": [],
                                "deliveryCycle": [],
                                "specialBilling": [],
                                "currency": "USD $"
                            },
                            "nonReturnParamsDetails": {
                                "orders": 0,
                                "boxes": 34,
                                "deliveryPoints": 10,
                                "weight": 0,
                                "volume": 10,
                                "distance": 43.43,
                                "loading": 0,
                                "unloading": 0,
                                "deliveryCycle": 0,
                                "specialBilling": 0
                            }
                        }
                    ]
                }
            ],
            "offeringDetails": {
                "transportCostDetails": {
                    "truckType": "1.3T 9.53M3",
                    "truckTypeId": "5ea07fd738811734c11bb0e9",
                    "cost": 97.43,
                    "nonReturnOfferingName": "1",
                    "nonReturnOfferingId": "61a8e5634395b54b0da5aad5",
                    "nonReturnChargesDetails": {
                        "orders": [],
                        "boxes": [
                            {
                                "type": "incremental",
                                "rangeStart": 1,
                                "rangeEnd": 9999,
                                "price": 2,
                                "_id": "62cc4de85b7dcfc692a2111f"
                            }
                        ],
                        "deliveryPoints": [
                            {
                                "type": "fixed",
                                "rangeStart": 1,
                                "rangeEnd": 9999,
                                "price": 10,
                                "_id": "62cc4de85b7dcfc692a2111e"
                            }
                        ],
                        "weight": [],
                        "volume": [
                            {
                                "type": "fixed",
                                "rangeStart": 1,
                                "rangeEnd": 9999,
                                "price": 10,
                                "_id": "62cc4de85b7dcfc692a2111d"
                            }
                        ],
                        "distance": [
                            {
                                "type": "incremental",
                                "rangeStart": 1,
                                "rangeEnd": 9999,
                                "price": 1,
                                "_id": "62cc4de85b7dcfc692a2111c"
                            }
                        ],
                        "loading": [],
                        "unloading": [],
                        "deliveryCycle": [],
                        "specialBilling": [],
                        "currency": "USD $"
                    },
                    "nonReturnParamsDetails": {
                        "orders": 0,
                        "boxes": 34,
                        "deliveryPoints": 10,
                        "weight": 0,
                        "volume": 10,
                        "distance": 43.43,
                        "loading": 0,
                        "unloading": 0,
                        "deliveryCycle": 0,
                        "specialBilling": 0
                    }
                },
                "serviceOfferingDetails": [
                    {
                        "totalAmount": 100,
                        "name": "Javilla Testing",
                        "id": "61a8e1d04395b54b0da5aa96",
                        "offeringId": "61a8e4dd4395b54b0da5aaa5",
                        "offeringName": "12",
                        "serviceType": {
                            "orders": "Total Per Load",
                            "boxes": "Total Per Load",
                            "deliveryPoints": "Total Per Load",
                            "weight": "Total Per Load",
                            "volume": "Total Per Load",
                            "distance": "Total Per Load",
                            "loading": "Total Per Load",
                            "unloading": "Total Per Load",
                            "deliveryCycle": "Total Per Order",
                            "specialBilling": "Per Product Volume"
                        },
                        "nonReturnPrice": 100,
                        "vehicleType": "1.3T 9.53M3",
                        "vehicleTypeId": "5ea07fd738811734c11bb0e9",
                        "chargesDetails": {
                            "orders": [],
                            "boxes": [
                                {
                                    "type": "fixed",
                                    "rangeStart": 1,
                                    "rangeEnd": 30,
                                    "price": 100,
                                    "_id": "62703060151afbbbc75282fc"
                                },
                                {
                                    "type": "fixed",
                                    "rangeStart": 31,
                                    "rangeEnd": 500,
                                    "price": 30,
                                    "_id": "62703060151afbbbc75282fb"
                                }
                            ],
                            "deliveryPoints": [],
                            "weight": [],
                            "volume": [],
                            "distance": [],
                            "loading": [],
                            "unloading": [],
                            "deliveryCycle": [],
                            "specialBilling": [],
                            "currency": "USD $"
                        },
                        "nonReturnChargesDetails": {
                            "orders": [],
                            "boxes": [
                                {
                                    "type": "fixed",
                                    "rangeStart": 1,
                                    "rangeEnd": 30,
                                    "price": 100,
                                    "_id": "62703060151afbbbc75282fc"
                                },
                                {
                                    "type": "fixed",
                                    "rangeStart": 31,
                                    "rangeEnd": 500,
                                    "price": 30,
                                    "_id": "62703060151afbbbc75282fb"
                                }
                            ],
                            "deliveryPoints": [],
                            "weight": [],
                            "volume": [],
                            "distance": [],
                            "loading": [],
                            "unloading": [],
                            "deliveryCycle": [],
                            "specialBilling": [],
                            "currency": "USD $"
                        },
                        "nonReturnParamsDetails": {
                            "orders": 0,
                            "boxes": 100,
                            "deliveryPoints": 0,
                            "weight": 0,
                            "volume": 0,
                            "distance": 0,
                            "loading": 0,
                            "unloading": 0,
                            "deliveryCycle": 0,
                            "specialBilling": 0
                        }
                    }
                ]
            },
            "selectedVehicle": {
                "_id": "62387ea85a2e724354978a3d",
                "driver_id": {
                    "_id": "62387dd55a2e724354978a39",
                    "transporter_id": "61a8e2c84395b54b0da5aa9d",
                    "updated_by": "admin@flai.com.do",
                    "created_by": null,
                    "createdAt": "2022-03-21T13:30:53.182Z",
                    "operator_photo": null,
                    "document_photo": null,
                    "rntt_photo": null,
                    "rntt_validity": "03/21/2022",
                    "rntt_id": "12345678",
                    "licence_photo": null,
                    "licence_validity": "03/21/2022",
                    "license_no": "12345678",
                    "vehicle_ids": [
                        "62387ea85a2e724354978a3d"
                    ],
                    "email": "kennymartinez19k@gmail.com",
                    "telephone": "8099808621",
                    "city": "distrito nacional",
                    "document_id": null,
                    "last_name": "Martinez",
                    "first_name": "Kenny",
                    "unavailableSchedule": [],
                    "isDeleted": false,
                    "__v": 0
                },
                "vehicle_type": "5ea07fd738811734c11bb0e9",
                "transporter_id": {
                    "_id": "61a8e2c84395b54b0da5aa9d",
                    "owned_by": "Driver",
                    "updated_by": null,
                    "created_group": "EXO",
                    "isactive": true,
                    "created_by": "admin@flai.com.do",
                    "createdAt": "2021-12-02T15:14:16.007Z",
                    "vehicle_ids": [
                        "61a8e3d84395b54b0da5aaa3",
                        "61ead4f37b01c63f6414e923",
                        "62387ea85a2e724354978a3d",
                        "625de2aa7be3c19868638944"
                    ],
                    "driver_ids": [
                        "61a8e3254395b54b0da5aa9f",
                        "61ead0c97b01c63f6414e8f5",
                        "62387dd55a2e724354978a39",
                        "625de2267be3c1986863893f"
                    ],
                    "telephone": [
                        "8094034881"
                    ],
                    "email": "mrmiguetara@gmail.com",
                    "position": "CEO",
                    "fullname": "Miguel Gonzalez",
                    "transport_costs": [],
                    "service_ids": [
                        "5e25c73aab0fa96b948fac60",
                        "5d9baef3adc86641605520b5",
                        "5d9663c0264344124585cd8f",
                        "5d84f1cc0f049242676e6447",
                        "5d81f93cd6279178eb58eeca",
                        "5d7b3bfac5b9e0246f35f1b8",
                        "5d77b8d85639bf5d74465ce5",
                        "5d7234757addb332460762e8"
                    ],
                    "effective_date": "12/02/2021",
                    "contract_file": null,
                    "contract_type": "Driver+Truck+Fuel",
                    "phone2": null,
                    "phone1": "8094034881",
                    "zipcode": "10505",
                    "address": "Paseo Sevilla #27",
                    "rnc": "566994",
                    "city": "distrito nacional",
                    "company_name": "Javilla Transport",
                    "isDeleted": false,
                    "__v": 0
                },
                "active": "true",
                "virtual": false,
                "updated_by": "admin@flai.com.do",
                "mileage": "10",
                "co2_emission": null,
                "additional_characterstic": null,
                "capacity_pallets": 4,
                "volume_capacity": 9.537,
                "load_capacity": 1180,
                "color": null,
                "license_no": "1221",
                "vin_no": null,
                "insurance_company": null,
                "policy_date": "2022-03-21T00:00:00.000Z",
                "policy_no": "1221",
                "vehicle_capacity": null,
                "vehicle_no": "3",
                "created_by": "admin@flai.com.do",
                "createdAt": "2022-03-21T13:33:28.446Z",
                "vin_photo": null,
                "insurence_photo": null,
                "vehicle_photo": null,
                "driver": "Kenny Martinez",
                "year": "2022",
                "type": "1.3T 9.53M3",
                "model": "f150",
                "vehicleTypeName": null,
                "isDeleted": false,
                "brand": "Ford",
                "__v": 0,
                "gpsId": "15788",
                "gpsProvider": "Telematics",
                "maximum_trips_per_day": 3
            }
        }
    },
    "Orders": [
        {
            "_id": "641238be841713a7f50430d0",
            "order_num": "1100231051",
            "customer": {
                "_id": "61a8e1d04395b54b0da5aa96",
                "zoneGroup": "61a8e21a4395b54b0da5aa98",
                "updated_by": null,
                "created_group": "EXO",
                "created_by": "admin@flai.com.do",
                "createdAt": "2021-12-02T15:10:08.016Z",
                "contact_ids": [
                    null
                ],
                "email": "mrmiguetara@gmail.com",
                "contacts": [
                    {}
                ],
                "telephone2": "",
                "telephone1": "8094034881",
                "website": "http://mrmiguetara.me",
                "RNC_no": "12345678946",
                "description": "",
                "color": "",
                "icon": null,
                "postal_code": "125050",
                "tax_id": "u6777",
                "industry": "Retail",
                "active": "true",
                "address": "45",
                "city": "Santo Domingo",
                "country": "Dominican Republic",
                "rating": null,
                "name": "Javilla Testing",
                "isDeleted": false,
                "__v": 0
            },
            "rejectedTimestamp": null,
            "deliveryTimestamp": null,
            "price": 11.76,
            "serviceType": "FTL",
            "deliveryAttempted": [],
            "exceptions": [],
            "products": [
                {
                    "exceptionRaised": false,
                    "product": "61a8e66d4395b54b0da5ab05",
                    "name": "10",
                    "status": null,
                    "quantity": 2,
                    "quantityBefore": null,
                    "overRideTotalUnit": null,
                    "qrCode": "8",
                    "defaultQRCode": null,
                    "loaded": false,
                    "weight": 40,
                    "volume": 0.016,
                    "scaningTimestamp": "2023-03-15T21:29:34.079Z",
                    "unitWeight": 20,
                    "unitVolume": 0.008,
                    "loadingTimestamp": null,
                    "deliveryTimestamp": null,
                    "measurementUnit": "cm",
                    "scanOneByOne": "yes",
                    "loadScanningCounter": 0,
                    "description": "Oro puro del bueno",
                    "contains": null,
                    "specialHandlingAndBillingType": null,
                    "damagedChargeCurrency": "USD",
                    "damagedChargePrice": 0,
                    "_id": "641238be841713a7f50430d1"
                }
            ],
            "warehouse": "5e184b8ac86dd63a98d322da",
            "transporter_id": "61a8e2c84395b54b0da5aa9d",
            "finalOrderLocation": {
                "lat": null,
                "lng": null
            },
            "addAdditionalInfo": [],
            "deliveryImages": null,
            "created_group": "EXO",
            "type": "loads",
            "comment_by": null,
            "comment": null,
            "islatest": true,
            "isactive": true,
            "created_by": "admin@flai.com.do",
            "createdAt": "2023-03-15T21:29:34.175Z",
            "optimizerTimestamp": null,
            "perLoadState": [
                {
                    "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                    "state": "Assigned",
                    "loadingTimestampStart": null,
                    "loadingTimestampEnd": null,
                    "warehouse": "AJFA-Test",
                    "timeslot": "15:25 - 15:45",
                    "loadDate": "Sun Apr 30 2023 20:35:30 GMT+0000 (Coordinated Universal Time)",
                    "bay": "Bay 1",
                    "assignTimeStamp": "2023-04-30T20:35:30.396Z",
                    "exceptions": [],
                    "deliveryAttempted": [],
                    "serviceType": null,
                    "price": null,
                    "deliveryTimestamp": null,
                    "rejectedTimestamp": null,
                    "loadDetails": {
                        "vehicleNumber": "3",
                        "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                        "transporterName": "Javilla Transport",
                        "vehicleId": "62387ea85a2e724354978a3d",
                        "loadId": "644ebfcbe9216d3cb5256171",
                        "vehicleType": "5ea07fd738811734c11bb0e9",
                        "driverName": "Kenny Martinez"
                    },
                    "deliveryImages": null,
                    "loadId": "644ebfcbe9216d3cb5256171",
                    "_id": "644ed1125f5dc8433eb12b13",
                    "returnServiceOffering": null,
                    "serviceOffering": "61a8e4dd4395b54b0da5aaa5"
                }
            ],
            "status": "Assigned",
            "imported_filename": "Orders (1) (61) (1) (54).xlsx",
            "providerZone": "5eda5261cb707d20b6d16d59",
            "zone": "61a8e2584395b54b0da5aa9a",
            "no_of_boxes": 2,
            "volume": 0.016,
            "authorized_by": "flaiAdmin",
            "final_price": null,
            "weight": 40,
            "pickup_time": null,
            "pickup_date": null,
            "expected_time": "23:00",
            "expected_date": "2023-03-18T23:00:00.000Z",
            "cost": 22.01,
            "hasAssociatedOrder": false,
            "deliveryCycle": null,
            "autoCreateReturnOrder": false,
            "isReturn": false,
            "latitude": 18.5290574,
            "longitude": -69.9107115,
            "zipCode": "10111",
            "province": "santo domingo",
            "city": "distrito nacional",
            "sector": "bella vista",
            "address": "km. 22, los mina  edif. e9-15. santo domingo este",
            "countryCode": null,
            "phone": null,
            "email": null,
            "Official_ID": null,
            "client_name": "Wilson",
            "client_id": "31",
            "__v": 0,
            "loadDetails": {
                "vehicleNumber": "3",
                "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                "transporterName": "Javilla Transport",
                "vehicleId": "62387ea85a2e724354978a3d",
                "loadId": "644ebfcbe9216d3cb5256171",
                "vehicleType": "5ea07fd738811734c11bb0e9",
                "driverName": "Kenny Martinez"
            },
            "returnServiceOffering": null,
            "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
            "boxesLoaded": 0,
            "boxesDelivered": 0
        },
        {
            "_id": "6414cabc1779c41c3823aa87",
            "order_num": "1100231104",
            "customer": {
                "_id": "61a8e1d04395b54b0da5aa96",
                "zoneGroup": "61a8e21a4395b54b0da5aa98",
                "updated_by": null,
                "created_group": "EXO",
                "created_by": "admin@flai.com.do",
                "createdAt": "2021-12-02T15:10:08.016Z",
                "contact_ids": [
                    null
                ],
                "email": "mrmiguetara@gmail.com",
                "contacts": [
                    {}
                ],
                "telephone2": "",
                "telephone1": "8094034881",
                "website": "http://mrmiguetara.me",
                "RNC_no": "12345678946",
                "description": "",
                "color": "",
                "icon": null,
                "postal_code": "125050",
                "tax_id": "u6777",
                "industry": "Retail",
                "active": "true",
                "address": "45",
                "city": "Santo Domingo",
                "country": "Dominican Republic",
                "rating": null,
                "name": "Javilla Testing",
                "isDeleted": false,
                "__v": 0
            },
            "rejectedTimestamp": null,
            "deliveryTimestamp": "2023-03-30T13:27:26.295Z",
            "price": 88.24,
            "serviceType": "FTL",
            "deliveryAttempted": [],
            "exceptions": [],
            "products": [
                {
                    "exceptionRaised": false,
                    "product": "61a8e66d4395b54b0da5ab05",
                    "name": "10",
                    "status": "",
                    "quantity": 15,
                    "quantityBefore": null,
                    "overRideTotalUnit": null,
                    "qrCode": "3",
                    "defaultQRCode": null,
                    "loaded": false,
                    "weight": 300,
                    "volume": 0.12,
                    "scaningTimestamp": "2023-03-17T20:17:00.522Z",
                    "unitWeight": 20,
                    "unitVolume": 0.008,
                    "loadingTimestamp": null,
                    "deliveryTimestamp": "2023-03-30T13:27:17.430Z",
                    "measurementUnit": "cm",
                    "scanOneByOne": "no",
                    "loadScanningCounter": 0,
                    "description": "Oro puro del bueno",
                    "contains": null,
                    "specialHandlingAndBillingType": null,
                    "damagedChargeCurrency": "USD",
                    "damagedChargePrice": 0,
                    "_id": "64184ca91779c41c3823aab0"
                }
            ],
            "warehouse": "5e184b8ac86dd63a98d322da",
            "transporter_id": "61a8e2c84395b54b0da5aa9d",
            "finalOrderLocation": {
                "lat": 18.5304427,
                "lng": -69.8041564
            },
            "addAdditionalInfo": [],
            "deliveryImages": null,
            "created_group": "EXO",
            "type": "loads",
            "comment_by": null,
            "comment": null,
            "islatest": true,
            "isactive": true,
            "created_by": "admin@flai.com.do",
            "createdAt": "2023-03-17T20:17:00.571Z",
            "optimizerTimestamp": null,
            "perLoadState": [
                {
                    "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                    "state": "Assigned",
                    "loadingTimestampStart": null,
                    "loadingTimestampEnd": null,
                    "warehouse": "AJFA-Test",
                    "timeslot": "15:25 - 15:45",
                    "loadDate": "Sun Apr 30 2023 20:35:27 GMT+0000 (Coordinated Universal Time)",
                    "bay": "Bay 1",
                    "assignTimeStamp": "2023-04-30T20:35:27.918Z",
                    "exceptions": [],
                    "deliveryAttempted": [],
                    "serviceType": null,
                    "price": null,
                    "deliveryTimestamp": null,
                    "rejectedTimestamp": null,
                    "loadDetails": {
                        "vehicleNumber": "3",
                        "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                        "transporterName": "Javilla Transport",
                        "vehicleId": "62387ea85a2e724354978a3d",
                        "loadId": "644ebfcbe9216d3cb5256171",
                        "vehicleType": "5ea07fd738811734c11bb0e9",
                        "driverName": "Kenny Martinez"
                    },
                    "deliveryImages": null,
                    "loadId": "644ebfcbe9216d3cb5256171",
                    "_id": "644ed10f5f5dc8433eb12b0e",
                    "returnServiceOffering": null,
                    "serviceOffering": "61a8e4dd4395b54b0da5aaa5"
                }
            ],
            "status": "Assigned",
            "imported_filename": "Orders (1) (61) (1) (57).xlsx",
            "providerZone": "5eda5261cb707d20b6d16d58",
            "zone": "61a8e2584395b54b0da5aa9a",
            "no_of_boxes": 15,
            "volume": 0.12,
            "authorized_by": "flaiAdmin",
            "final_price": null,
            "weight": 300,
            "pickup_time": "NaN:NaN",
            "pickup_date": null,
            "expected_time": "23:0",
            "expected_date": "2023-03-20T23:00:00.000Z",
            "cost": 75.42,
            "hasAssociatedOrder": false,
            "deliveryCycle": null,
            "autoCreateReturnOrder": false,
            "isReturn": false,
            "latitude": 18.5126035,
            "longitude": -69.8001645,
            "zipCode": "10111",
            "province": "santo domingo",
            "city": "distrito nacional",
            "sector": "bella vista",
            "address": "km. 22, los mina  edif. e9-15. santo domingo este",
            "countryCode": "1",
            "phone": "8299808621",
            "email": "km@gm.com",
            "Official_ID": null,
            "client_name": "Wilson",
            "client_id": "31",
            "__v": 0,
            "orderSequence": null,
            "loadDetails": {
                "vehicleNumber": "3",
                "loadNumber": "AJFA-Test 04/30/2023 3:25PM Gate 01",
                "transporterName": "Javilla Transport",
                "vehicleId": "62387ea85a2e724354978a3d",
                "loadId": "644ebfcbe9216d3cb5256171",
                "vehicleType": "5ea07fd738811734c11bb0e9",
                "driverName": "Kenny Martinez"
            },
            "returnServiceOffering": null,
            "serviceOffering": "61a8e4dd4395b54b0da5aaa5",
            "boxesLoaded": 0,
            "boxesDelivered": 1
        }
    ],
    "Vehicles": [
        {
            "maximum_trips_per_day": 3,
            "gpsProvider": "Telematics",
            "gpsId": "15788",
            "__v": 0,
            "brand": "Ford",
            "isDeleted": false,
            "vehicleTypeName": null,
            "model": "f150",
            "type": "1.3T 9.53M3",
            "year": "2022",
            "driver": "Kenny Martinez",
            "vehicle_photo": null,
            "insurence_photo": null,
            "vin_photo": null,
            "createdAt": "2022-03-21T13:33:28.446Z",
            "created_by": "admin@flai.com.do",
            "vehicle_no": "3",
            "vehicle_capacity": null,
            "policy_no": "1221",
            "policy_date": "2022-03-21T00:00:00.000Z",
            "insurance_company": null,
            "vin_no": null,
            "license_no": "1221",
            "color": null,
            "load_capacity": 1180,
            "volume_capacity": 9.537,
            "capacity_pallets": 4,
            "additional_characterstic": null,
            "co2_emission": null,
            "mileage": "10",
            "updated_by": "admin@flai.com.do",
            "virtual": false,
            "active": "true",
            "transporter_id": {
                "__v": 0,
                "isDeleted": false,
                "company_name": "Javilla Transport",
                "city": "distrito nacional",
                "rnc": "566994",
                "address": "Paseo Sevilla #27",
                "zipcode": "10505",
                "phone1": "8094034881",
                "phone2": null,
                "contract_type": "Driver+Truck+Fuel",
                "contract_file": null,
                "effective_date": "12/02/2021",
                "service_ids": [
                    "5e25c73aab0fa96b948fac60",
                    "5d9baef3adc86641605520b5",
                    "5d9663c0264344124585cd8f",
                    "5d84f1cc0f049242676e6447",
                    "5d81f93cd6279178eb58eeca",
                    "5d7b3bfac5b9e0246f35f1b8",
                    "5d77b8d85639bf5d74465ce5",
                    "5d7234757addb332460762e8"
                ],
                "transport_costs": [],
                "fullname": "Miguel Gonzalez",
                "position": "CEO",
                "email": "mrmiguetara@gmail.com",
                "telephone": [
                    "8094034881"
                ],
                "driver_ids": [
                    "61a8e3254395b54b0da5aa9f",
                    "61ead0c97b01c63f6414e8f5",
                    "62387dd55a2e724354978a39",
                    "625de2267be3c1986863893f"
                ],
                "vehicle_ids": [
                    "61a8e3d84395b54b0da5aaa3",
                    "61ead4f37b01c63f6414e923",
                    "62387ea85a2e724354978a3d",
                    "625de2aa7be3c19868638944"
                ],
                "createdAt": "2021-12-02T15:14:16.007Z",
                "created_by": "admin@flai.com.do",
                "isactive": true,
                "created_group": "EXO",
                "updated_by": null,
                "owned_by": "Driver",
                "_id": "61a8e2c84395b54b0da5aa9d"
            },
            "vehicle_type": "5ea07fd738811734c11bb0e9",
            "driver_id": {
                "__v": 0,
                "isDeleted": false,
                "unavailableSchedule": [],
                "first_name": "Kenny",
                "last_name": "Martinez",
                "document_id": null,
                "city": "distrito nacional",
                "telephone": "8099808621",
                "email": "kennymartinez19k@gmail.com",
                "vehicle_ids": [
                    "62387ea85a2e724354978a3d"
                ],
                "license_no": "12345678",
                "licence_validity": "03/21/2022",
                "licence_photo": null,
                "rntt_id": "12345678",
                "rntt_validity": "03/21/2022",
                "rntt_photo": null,
                "document_photo": null,
                "operator_photo": null,
                "createdAt": "2022-03-21T13:30:53.182Z",
                "created_by": null,
                "updated_by": "admin@flai.com.do",
                "transporter_id": "61a8e2c84395b54b0da5aa9d",
                "_id": "62387dd55a2e724354978a39"
            },
            "_id": "62387ea85a2e724354978a3d"
        }
    ],
    "approvers": [
        {
            "sentDate": "01/05/2023",
            "updatedOn": "01/05/2023",
            "status": "ACCEPTED",
            "_id": "644fee88376c6b69f9978dad",
            "approver_id": {
                "_id": "614e303a9cc2bc06f1fcac0e",
                "user_type": "Provider",
                "email": "rezuelve@gmail.com"
            }
        },
        {
            "sentDate": "01/05/2023",
            "updatedOn": "01/05/2023",
            "status": "ACCEPTED",
            "_id": "644feead376c6b69f9978db0",
            "approver_id": {
                "_id": "62387dd55a2e724354978a39",
                "user_type": "Driver",
                "email": "kennymartinez19k@gmail.com"
            }
        }
    ],
    "slotTimeStamp": {
        "end_time": "15:45",
        "start_time": "15:25",
        "date": "2023-04-30T00:00:00.000Z"
    },
    "loadMapId": "644ebfcbe9216d3cb5256171",
    "name": "Bay 1"
}
    }
   },
   mounted(){
    this.getNumberProduct()
   },
   methods:{
    getNumberProduct(){
        console.log('====================================');
        console.log();
        console.log('====================================');
    }
   }
}
</script>

<style>

</style>