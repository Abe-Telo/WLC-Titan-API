# WLC-Titan-API
WLC TO GDMS
{
	"info": {
		"_postman_id": "64aafb99-362e-469b-b54c-f11b00b8de6d",
		"name": "Titan API",
		"description": "Titan is your API gateway to UC Communications.  \nThe URL endpoint is:  \n`https://api.titan.host/api/v2`\n\n![Titan Logo](https://docs.titan.host/Graphic01_WhiteBG_PNG.png)\n",
		"schema": "https://schema.getpostman.com/json/collection/v2.1.0/collection.json",
		"_uid": "24886105-64aafb99-362e-469b-b54c-f11b00b8de6d"
	},
	"item": [
		{
			"name": "callqueues",
			"item": [
				{
					"name": "Get call queue list",
					"id": "4f952771-2160-42a0-8548-ce03bf2dd840",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/callqueues",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"callqueues"
							]
						},
						"description": "Get call queue list"
					},
					"response": [
						{
							"id": "17ca40ce-02c5-4340-bdce-7f704cd87d7c",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/callqueues",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"callqueues"
									]
								},
								"description": "Get call queue list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 62364900,\n  \"data\": [\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"mollit anim\",\n          \"name\": \"do anim in proident\"\n        },\n        \"created_at\": \"do\",\n        \"enabled\": false,\n        \"id\": \"laboris Duis nisi aliquip\",\n        \"master_account_id\": \"est esse occaecat\",\n        \"name\": \"minim labori\",\n        \"reseller_id\": 3065208,\n        \"sales_person\": {\n          \"first_name\": \"eiusmod commodo labore in\",\n          \"id\": \"ea\",\n          \"last_name\": \"aute\"\n        },\n        \"timezone\": \"dolore cillum velit ad\",\n        \"updated_at\": \"id labore exercitation esse in\",\n        \"website\": \"quis\"\n      },\n      \"call_routing_type\": \"labore Lorem\",\n      \"caller_id_prepend\": \"nulla\",\n      \"created_at\": \"dol\",\n      \"e911_registration\": {\n        \"callback_number_id\": 9740530,\n        \"id26\": \"Duis irure exercitation\",\n        \"name\": \"sit enim nisi nulla id\"\n      },\n      \"holiday1\": \"reprehenderit ea velit id\",\n      \"holiday2\": \"id\",\n      \"id\": 731460,\n      \"id26\": \"labore velit\",\n      \"inbound_cnam_dip\": true,\n      \"main_number\": false,\n      \"main_number_last_updated\": \"reprehenderit tempor E\",\n      \"outbound_caller_id\": \"irure\",\n      \"pbx_connector\": {\n        \"id\": -29142292,\n        \"name\": \"deserunt non cillum pariatur in\"\n      },\n      \"phone_number\": \"deserun\",\n      \"phone_number_status\": {\n        \"id\": -99183854,\n        \"name\": \"qui magna et officia\"\n      },\n      \"reseller\": {\n        \"address_city\": \"dolor minim non ex\",\n        \"address_country\": \"exercitation ipsum\",\n        \"address_street_1\": \"com\",\n        \"address_street_2\": \"labore sunt deserunt\",\n        \"address_zip\": \"veniam\",\n        \"company_name\": \"proident reprehenderit laborum incididunt amet\",\n        \"connectwise_integrated\": true,\n        \"created_at\": \"elit consequat e\",\n        \"dba\": \"cillum ut\",\n        \"demo_mode\": true,\n        \"enabled\": false,\n        \"id26\": \"esse\"\n      },\n      \"routing_to1\": \"nulla dolor sint ad Excepteur\",\n      \"routing_to2\": \"mollit\",\n      \"sms_routing\": -90012399,\n      \"status\": \"in eu adipisicing consequat\",\n      \"t38_faxing\": true,\n      \"updated_at\": \"esse nulla Lorem\"\n    },\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"adipisicing voluptate ad\",\n          \"name\": \"reprehenderit vel\"\n        },\n        \"created_at\": \"ad anim ullamco proident ut\",\n        \"enabled\": true,\n        \"id\": \"qui \",\n        \"master_account_id\": \"ut commodo cillum sint\",\n        \"name\": \"ipsum non exercitation voluptate\",\n        \"reseller_id\": 37753806,\n        \"sales_person\": {\n          \"first_name\": \"id\",\n          \"id\": \"cupidatat esse dolore voluptate\",\n          \"last_name\": \"Excepteur ut\"\n        },\n        \"timezone\": \"sit occaecat in\",\n        \"updated_at\": \"in anim esse\",\n        \"website\": \"magna dolor aliquip cillum ullamco\"\n      },\n      \"call_routing_type\": \"in cupidatat aliquip\",\n      \"caller_id_prepend\": \"ex magna amet est\",\n      \"created_at\": \"ullamco minim\",\n      \"e911_registration\": {\n        \"callback_number_id\": -70545644,\n        \"id26\": \"Lorem minim\",\n        \"name\": \"irure exercitation\"\n      },\n      \"holiday1\": \"nisi pariatur aliq\",\n      \"holiday2\": \"velit ut reprehenderit\",\n      \"id\": -28736952,\n      \"id26\": \"dolor tempor\",\n      \"inbound_cnam_dip\": false,\n      \"main_number\": true,\n      \"main_number_last_updated\": \"veniam laboris nostrud\",\n      \"outbound_caller_id\": \"Ut proident m\",\n      \"pbx_connector\": {\n        \"id\": 83725421,\n        \"name\": \"proident adipisicing reprehenderit\"\n      },\n      \"phone_number\": \"nulla deserunt\",\n      \"phone_number_status\": {\n        \"id\": -73876935,\n        \"name\": \"fugiat ipsum dolore dolor\"\n      },\n      \"reseller\": {\n        \"address_city\": \"reprehenderit esse enim\",\n        \"address_country\": \"aliquip pariatur\",\n        \"address_street_1\": \"dolo\",\n        \"address_street_2\": \"nostrud laboris sint\",\n        \"address_zip\": \"enim\",\n        \"company_name\": \"ex dolore\",\n        \"connectwise_integrated\": true,\n        \"created_at\": \"in consequat commodo ut\",\n        \"dba\": \"pariatur et\",\n        \"demo_mode\": true,\n        \"enabled\": false,\n        \"id26\": \"laborum dolor\"\n      },\n      \"routing_to1\": \"commodo voluptate\",\n      \"routing_to2\": \"nulla pariatur est culpa\",\n      \"sms_routing\": -86754817,\n      \"status\": \"nostrud ad officia amet\",\n      \"t38_faxing\": false,\n      \"updated_at\": \"sint amet do qui\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -63945595,\n    \"page\": 42297442,\n    \"total_pages\": 54098389,\n    \"total_rows\": -25430239\n  },\n  \"request_id\": \"fugiat ut laborum incididunt\",\n  \"status\": \"cupidatat ad\"\n}"
						}
					]
				},
				{
					"name": "Get call queue details",
					"id": "b02aac62-27d4-472f-81c1-764902cc9554",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/callqueues/:callqueue_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"callqueues",
								":callqueue_idorid26"
							],
							"variable": [
								{
									"key": "callqueue_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of call queue"
								}
							]
						},
						"description": "Get call queue details"
					},
					"response": [
						{
							"id": "c6bdcf10-b801-4a1b-83bb-a39e36d4f3cb",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/callqueues/:callqueue_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"callqueues",
										":callqueue_idorid26"
									],
									"variable": [
										{
											"key": "callqueue_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of call queue"
										}
									]
								},
								"description": "Get call queue details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 48285299,\n  \"data\": {\n    \"account\": {\n      \"agent\": {\n        \"id\": \"velit non\",\n        \"name\": \"anim ex occaecat enim ut\"\n      },\n      \"created_at\": \"minim voluptate\",\n      \"enabled\": true,\n      \"id\": \"dolor in sed id dolor\",\n      \"master_account_id\": \"ut aliqua exercitation culpa ullam\",\n      \"name\": \"consectetur sint et adipisicing in\",\n      \"reseller_id\": 54494245,\n      \"sales_person\": {\n        \"first_name\": \"cillum\",\n        \"id\": \"quis\",\n        \"last_name\": \"dolore proident\"\n      },\n      \"timezone\": \"ipsum eu non\",\n      \"updated_at\": \"ipsum id tempor aliqua\",\n      \"website\": \"deserunt\"\n    },\n    \"call_routing_type\": \"aute tempor minim in ex\",\n    \"caller_id_prepend\": \"proident nisi\",\n    \"created_at\": \"reprehenderit Duis dolore\",\n    \"e911_registration\": {\n      \"callback_number_id\": -34110543,\n      \"id26\": \"Exc\",\n      \"name\": \"exercitation non\"\n    },\n    \"holiday1\": \"elit enim veniam dolor\",\n    \"holiday2\": \"ut magna nulla do\",\n    \"id\": -96087886,\n    \"id26\": \"id elit\",\n    \"inbound_cnam_dip\": false,\n    \"main_number\": true,\n    \"main_number_last_updated\": \"reprehenderit quis dolore Lorem\",\n    \"outbound_caller_id\": \"dolor\",\n    \"pbx_connector\": {\n      \"id\": 86842860,\n      \"name\": \"sit in quis sint\"\n    },\n    \"phone_number\": \"velit ad quis officia\",\n    \"phone_number_status\": {\n      \"id\": -38661276,\n      \"name\": \"ut fugiat\"\n    },\n    \"reseller\": {\n      \"address_city\": \"occaecat\",\n      \"address_country\": \"sunt sit pariatur\",\n      \"address_street_1\": \"occaecat dolor\",\n      \"address_street_2\": \"pariatur\",\n      \"address_zip\": \"esse Excepteur incididunt\",\n      \"company_name\": \"cupidatat Ut fugiat minim\",\n      \"connectwise_integrated\": false,\n      \"created_at\": \"dolore veniam\",\n      \"dba\": \"Excepteur in\",\n      \"demo_mode\": false,\n      \"enabled\": true,\n      \"id26\": \"dolore culpa sed nisi aliqua\"\n    },\n    \"routing_to1\": \"aliqua\",\n    \"routing_to2\": \"dolore\",\n    \"sms_routing\": -14560573,\n    \"status\": \"sed\",\n    \"t38_faxing\": false,\n    \"updated_at\": \"anim aute id\"\n  },\n  \"request_id\": \"ut labore ullamc\",\n  \"status\": \"amet dolore\"\n}"
						}
					]
				}
			],
			"id": "d08d4b0d-4598-4631-8f5e-13d409578ec7"
		},
		{
			"name": "conferences",
			"item": [
				{
					"name": "Get conference list",
					"id": "13b29843-b360-4f75-8c48-39eaa99fbb48",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/conferences",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"conferences"
							]
						},
						"description": "Get conference list"
					},
					"response": [
						{
							"id": "f0b1066f-1085-4bb7-bc49-e5cbcaa8db6c",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/conferences",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"conferences"
									]
								},
								"description": "Get conference list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 60587574,\n  \"data\": [\n    {\n      \"assigned_to\": {\n        \"extension\": \"mollit irure tempor\",\n        \"first_name\": \"Excepteur nulla\",\n        \"id\": 63188163,\n        \"last_name\": \"reprehenderit de\"\n      },\n      \"created_at\": \"cillum sed eu\",\n      \"device_user_id\": -99620189,\n      \"id\": -39667782,\n      \"id26\": \"laboris dolore non incididunt anim\",\n      \"join_deaf\": true,\n      \"join_muted\": true,\n      \"moderator_pin\": \"velit dolor elit\",\n      \"moderators\": [\n        {\n          \"non_72\": false\n        },\n        {\n          \"veniam489\": 17377416,\n          \"voluptatefe7\": -57578710,\n          \"exercitation76\": -20166753.675382897,\n          \"dolorf19\": false\n        }\n      ],\n      \"name\": \"ex elit\",\n      \"numbers\": \"minim consequ\",\n      \"pin\": -74480122,\n      \"site\": {\n        \"id\": -21889453,\n        \"name\": \"est dolore Lorem ad enim\"\n      },\n      \"updated_at\": \"tempor est sed\"\n    },\n    {\n      \"assigned_to\": {\n        \"extension\": \"sed do eiusmod\",\n        \"first_name\": \"elit dolore laborum aliquip proident\",\n        \"id\": -44909350,\n        \"last_name\": \"pariatur\"\n      },\n      \"created_at\": \"voluptate esse\",\n      \"device_user_id\": 14455829,\n      \"id\": 25600569,\n      \"id26\": \"sint laboris nisi in\",\n      \"join_deaf\": true,\n      \"join_muted\": true,\n      \"moderator_pin\": \"nulla id minim commodo\",\n      \"moderators\": [\n        {\n          \"est_1_\": true,\n          \"incididunt477\": true\n        },\n        {\n          \"elitd\": -13918959,\n          \"quisb\": false\n        }\n      ],\n      \"name\": \"laborum ut dolor minim sint\",\n      \"numbers\": \"Duis magna enim qui Ut\",\n      \"pin\": 11564729,\n      \"site\": {\n        \"id\": -51844831,\n        \"name\": \"et ea aute\"\n      },\n      \"updated_at\": \"est labore\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -71883478,\n    \"page\": -13882383,\n    \"total_pages\": 40042824,\n    \"total_rows\": -53841654\n  },\n  \"request_id\": \"eiusmod consequat mollit pr\",\n  \"status\": \"dolor ipsum\"\n}"
						}
					]
				},
				{
					"name": "Get conference details",
					"id": "d374d647-b353-478f-a066-a91d885a788a",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/conferences/:conference_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"conferences",
								":conference_idorid26"
							],
							"variable": [
								{
									"key": "conference_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of conference"
								}
							]
						},
						"description": "Get conference details"
					},
					"response": [
						{
							"id": "531a264f-dd33-4685-8dbe-2870f1feb43f",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/conferences/:conference_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"conferences",
										":conference_idorid26"
									],
									"variable": [
										{
											"key": "conference_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of conference"
										}
									]
								},
								"description": "Get conference details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 24876400,\n  \"data\": {\n    \"assigned_to\": {\n      \"extension\": \"tempor esse sit\",\n      \"first_name\": \"dolor\",\n      \"id\": -68006056,\n      \"last_name\": \"ex et aliqua veniam\"\n    },\n    \"created_at\": \"cupidatat esse\",\n    \"device_user_id\": 48831061,\n    \"id\": 3973475,\n    \"id26\": \"amet\",\n    \"join_deaf\": true,\n    \"join_muted\": true,\n    \"moderator_pin\": \"veniam sunt ex\",\n    \"moderators\": [\n      {\n        \"animc55\": \"nostrud in officia quis elit\",\n        \"proident_7\": false,\n        \"veniam_05d\": 26611656.579667374\n      },\n      {\n        \"dolor8a\": -70324477,\n        \"in_994\": \"deserunt Lorem nulla ea\",\n        \"autecee\": \"Lorem aliqua dolor qui\"\n      }\n    ],\n    \"name\": \"dolor incididunt nulla minim esse\",\n    \"numbers\": \"e\",\n    \"pin\": 68765898,\n    \"site\": {\n      \"id\": -55581651,\n      \"name\": \"aliqua ut tempor amet commodo\"\n    },\n    \"updated_at\": \"exercitation ut\"\n  },\n  \"request_id\": \"elit ut enim aliquip amet\",\n  \"status\": \"tempor in est ullamco\"\n}"
						}
					]
				}
			],
			"id": "9626aaa8-6b0c-4b79-9f3e-ea8304bd147b"
		},
		{
			"name": "devices",
			"item": [
				{
					"name": "Get device list",
					"id": "ddcbcff1-7698-43c7-a193-de252a064332",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/devices",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"devices"
							]
						},
						"description": "Get device list"
					},
					"response": [
						{
							"id": "5591f375-1997-4b32-a353-94637210658c",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/devices",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"devices"
									]
								},
								"description": "Get device list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 17275470,\n  \"data\": [\n    {\n      \"CELT_48\": false,\n      \"CELT_64\": false,\n      \"G722_16\": false,\n      \"G722_32\": false,\n      \"PCMA\": false,\n      \"PCMU\": true,\n      \"additional_emails\": \"adipisicing\",\n      \"custom_code\": \"in velit cupidatat veniam voluptate\",\n      \"device_line_keys\": [\n        {\n          \"data\": \"ut quis\",\n          \"device_id\": 55087379,\n          \"id\": 601980,\n          \"line_key_type\": \"qui proident nulla Duis\",\n          \"line_key_type_id\": -13185509,\n          \"num\": -53196029,\n          \"title\": \"sed aute\"\n        },\n        {\n          \"data\": \"est ex do magna\",\n          \"device_id\": -76340344,\n          \"id\": 44322071,\n          \"line_key_type\": \"D\",\n          \"line_key_type_id\": 38265479,\n          \"num\": 22576261,\n          \"title\": \"ex\"\n        }\n      ],\n      \"device_template\": {\n        \"id\": 11292139,\n        \"manufacturer_id\": 19382348,\n        \"name\": \"cillum ad cupidatat laborum\"\n      },\n      \"device_type\": \"Ut irure sed dolore non\",\n      \"device_user\": {\n        \"extension\": \"eiusmod commodo amet incididunt\",\n        \"first_name\": \"ad\",\n        \"id\": 48426729,\n        \"last_name\": \"mollit cupidatat de\"\n      },\n      \"encryption\": -72432581,\n      \"encryption_type\": \"commodo nulla\",\n      \"expire_seconds\": 76039796,\n      \"extension\": \"elit occaecat sit deserunt\",\n      \"has_voicemail\": -53511489,\n      \"id\": -70832680,\n      \"id26\": \"pariatur deserunt aute adipisicing consequat\",\n      \"invite_format\": \"minim est cupidatat\",\n      \"keep_caller_id\": false,\n      \"mac_address\": \"nostrud sunt\",\n      \"manufacturer\": {\n        \"id\": 74176835,\n        \"title\": \"irure occaecat fugiat sit\"\n      },\n      \"manufacturer_model\": {\n        \"id\": -8066048,\n        \"title\": \"dolor ut\"\n      },\n      \"manufacturer_ringer\": {\n        \"display_name\": \"in dolor sed\",\n        \"id\": -83083297,\n        \"manufacturer_id\": 14320079\n      },\n      \"media_category\": \"sit ut\",\n      \"media_category_type\": \"tempor in eiusmod consectetur voluptate\",\n      \"media_id\": \"pariatur mollit Excepteur cupidatat\",\n      \"name\": \"ipsum amet ullamco\",\n      \"number\": \"Lorem proident laborum\",\n      \"peer_to_peer\": \"elit sunt do enim\",\n      \"peer_to_peer_type\": \"minim in\",\n      \"phone\": {\n        \"phone_number\": \"pariatur\"\n      },\n      \"require_keypress\": true,\n      \"restrict_caribbean\": \"ea magna occaecat\",\n      \"restrict_did_us\": \"ut incididunt et\",\n      \"restrict_international\": \"non veniam proident\",\n      \"restrict_toll_us\": \"mollit reprehenderit anim cu\",\n      \"restrict_tollfree_us\": \"elit nisi\",\n      \"sip_authentication_method\": \"ut cillum aute pariatur in\",\n      \"sip_password\": \"anim laboris dolor veniam\",\n      \"sip_realm\": \"ullamco nulla\",\n      \"sip_username\": \"aute id sit\",\n      \"site\": {\n        \"id\": -12116008,\n        \"name\": \"officia et c\"\n      },\n      \"virtual_extension\": {\n        \"extension\": \"aliqua sint dolore Duis enim\",\n        \"id\": 82511312,\n        \"name\": \"e\"\n      },\n      \"vm_to_email_enabled\": -19132945,\n      \"voicemail_box\": {\n        \"additional_emails\": \"consequat fugiat enim\",\n        \"device_user_id\": 95327393,\n        \"id\": -9855255,\n        \"name\": \"elit veniam sint\"\n      },\n      \"voip_id\": \"ex minim ea veniam\"\n    },\n    {\n      \"CELT_48\": true,\n      \"CELT_64\": false,\n      \"G722_16\": true,\n      \"G722_32\": true,\n      \"PCMA\": true,\n      \"PCMU\": true,\n      \"additional_emails\": \"laboris eu proident\",\n      \"custom_code\": \"do sunt sit in\",\n      \"device_line_keys\": [\n        {\n          \"data\": \"no\",\n          \"device_id\": 48036942,\n          \"id\": 49954669,\n          \"line_key_type\": \"dolore sunt consectetur labore\",\n          \"line_key_type_id\": 51633872,\n          \"num\": -45490402,\n          \"title\": \"dolor velit quis ipsum\"\n        },\n        {\n          \"data\": \"ullamco sit\",\n          \"device_id\": 1410269,\n          \"id\": -67505534,\n          \"line_key_type\": \"pariatur\",\n          \"line_key_type_id\": -2919033,\n          \"num\": -21601036,\n          \"title\": \"mollit ut incididunt dolore dolore\"\n        }\n      ],\n      \"device_template\": {\n        \"id\": 48887541,\n        \"manufacturer_id\": -15729246,\n        \"name\": \"ex eu sint\"\n      },\n      \"device_type\": \"sit\",\n      \"device_user\": {\n        \"extension\": \"consequat sed tempor ea aliquip\",\n        \"first_name\": \"esse laboris\",\n        \"id\": 55845033,\n        \"last_name\": \"adipisicing sunt\"\n      },\n      \"encryption\": 12828588,\n      \"encryption_type\": \"culpa\",\n      \"expire_seconds\": 81009133,\n      \"extension\": \"fugiat deserunt occaecat in Lorem\",\n      \"has_voicemail\": -3173428,\n      \"id\": -38939188,\n      \"id26\": \"est Excepteur ea labore\",\n      \"invite_format\": \"quis sed\",\n      \"keep_caller_id\": true,\n      \"mac_address\": \"reprehenderit minim\",\n      \"manufacturer\": {\n        \"id\": 19585046,\n        \"title\": \"consectetur aute\"\n      },\n      \"manufacturer_model\": {\n        \"id\": -30857794,\n        \"title\": \"dolor pariatur consequat\"\n      },\n      \"manufacturer_ringer\": {\n        \"display_name\": \"minim nisi elit\",\n        \"id\": -30044118,\n        \"manufacturer_id\": -69302448\n      },\n      \"media_category\": \"do incididunt aliqua qui in\",\n      \"media_category_type\": \"adipisicing anim \",\n      \"media_id\": \"dolor minim dolore ullamco\",\n      \"name\": \"fugiat mollit et labore\",\n      \"number\": \"minim ad\",\n      \"peer_to_peer\": \"anim enim non culpa veniam\",\n      \"peer_to_peer_type\": \"in ea aute\",\n      \"phone\": {\n        \"phone_number\": \"consequat deserunt\"\n      },\n      \"require_keypress\": true,\n      \"restrict_caribbean\": \"Excepteur sed non cillum\",\n      \"restrict_did_us\": \"do non\",\n      \"restrict_international\": \"incididunt adipisicing cillum elit\",\n      \"restrict_toll_us\": \"Ut nostrud\",\n      \"restrict_tollfree_us\": \"in non\",\n      \"sip_authentication_method\": \"in culpa\",\n      \"sip_password\": \"cillum commodo aliquip dolore ut\",\n      \"sip_realm\": \"amet dolore Excepteur in laboris\",\n      \"sip_username\": \"ad mollit elit aute\",\n      \"site\": {\n        \"id\": -5620489,\n        \"name\": \"adipisicing\"\n      },\n      \"virtual_extension\": {\n        \"extension\": \"velit\",\n        \"id\": 47674792,\n        \"name\": \"cupidatat nostrud elit\"\n      },\n      \"vm_to_email_enabled\": -88491994,\n      \"voicemail_box\": {\n        \"additional_emails\": \"ut in nisi\",\n        \"device_user_id\": 77988671,\n        \"id\": -9153399,\n        \"name\": \"exercitation do\"\n      },\n      \"voip_id\": \"consectetur\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 38079937,\n    \"page\": -56063112,\n    \"total_pages\": -23940959,\n    \"total_rows\": 46592930\n  },\n  \"request_id\": \"nostrud id\",\n  \"status\": \"fugiat\"\n}"
						}
					]
				},
				{
					"name": "Get device details",
					"id": "f63d7239-f53d-4142-b1ac-d9f0bd64a710",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/devices/:device_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"devices",
								":device_idorid26"
							],
							"variable": [
								{
									"key": "device_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of device"
								}
							]
						},
						"description": "Get device details"
					},
					"response": [
						{
							"id": "78a4a63b-2bb6-4282-af69-bdbf20d8bcf8",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/devices/:device_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"devices",
										":device_idorid26"
									],
									"variable": [
										{
											"key": "device_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of device"
										}
									]
								},
								"description": "Get device details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 70037461,\n  \"data\": {\n    \"CELT_48\": false,\n    \"CELT_64\": true,\n    \"G722_16\": true,\n    \"G722_32\": true,\n    \"PCMA\": false,\n    \"PCMU\": false,\n    \"additional_emails\": \"aute aliqua\",\n    \"custom_code\": \"Excepteur inc\",\n    \"device_line_keys\": [\n      {\n        \"data\": \"nisi magna lab\",\n        \"device_id\": -50926835,\n        \"id\": 13648806,\n        \"line_key_type\": \"n\",\n        \"line_key_type_id\": 14901021,\n        \"num\": -71483461,\n        \"title\": \"nulla pariatur incididu\"\n      },\n      {\n        \"data\": \"ullamco aliquip\",\n        \"device_id\": 18872095,\n        \"id\": -60177720,\n        \"line_key_type\": \"exercitation ad\",\n        \"line_key_type_id\": 41197120,\n        \"num\": 84815201,\n        \"title\": \"in in\"\n      }\n    ],\n    \"device_template\": {\n      \"id\": -11138005,\n      \"manufacturer_id\": 2203791,\n      \"name\": \"consectetur quis est et mollit\"\n    },\n    \"device_type\": \"aliqua nisi c\",\n    \"device_user\": {\n      \"extension\": \"pariatur Excepteur cupidatat irure\",\n      \"first_name\": \"labore cupidatat\",\n      \"id\": 32312909,\n      \"last_name\": \"reprehenderit magna adipisicing\"\n    },\n    \"encryption\": -49916252,\n    \"encryption_type\": \"sed Duis ipsum cillum\",\n    \"expire_seconds\": -5888406,\n    \"extension\": \"et Lorem dolor elit officia\",\n    \"has_voicemail\": 74981129,\n    \"id\": 494455,\n    \"id26\": \"commodo Excepteur laboris nostrud in\",\n    \"invite_format\": \"cillum consectetur et Lorem\",\n    \"keep_caller_id\": false,\n    \"mac_address\": \"exercitation esse cupidatat\",\n    \"manufacturer\": {\n      \"id\": -2468139,\n      \"title\": \"mollit ullamco\"\n    },\n    \"manufacturer_model\": {\n      \"id\": -15033219,\n      \"title\": \"irure deserunt in\"\n    },\n    \"manufacturer_ringer\": {\n      \"display_name\": \"commodo veniam\",\n      \"id\": 78872111,\n      \"manufacturer_id\": 58054274\n    },\n    \"media_category\": \"ad cillum sunt Ut proident\",\n    \"media_category_type\": \"dolor proident\",\n    \"media_id\": \"ut est sint\",\n    \"name\": \"aliqua nulla Ut\",\n    \"number\": \"ut veniam reprehenderit\",\n    \"peer_to_peer\": \"ut velit cillum\",\n    \"peer_to_peer_type\": \"dolor elit ipsum Excepteur\",\n    \"phone\": {\n      \"phone_number\": \"labore\"\n    },\n    \"require_keypress\": true,\n    \"restrict_caribbean\": \"anim nulla sed in cillum\",\n    \"restrict_did_us\": \"reprehenderit sed aute\",\n    \"restrict_international\": \"Lorem sint\",\n    \"restrict_toll_us\": \"magna et dolore\",\n    \"restrict_tollfree_us\": \"i\",\n    \"sip_authentication_method\": \"es\",\n    \"sip_password\": \"voluptate quis est\",\n    \"sip_realm\": \"exercitation\",\n    \"sip_username\": \"adipisicing\",\n    \"site\": {\n      \"id\": -16234399,\n      \"name\": \"deserunt in occaecat\"\n    },\n    \"virtual_extension\": {\n      \"extension\": \"id\",\n      \"id\": 34418985,\n      \"name\": \"dolore sint quis consectetur cupidatat\"\n    },\n    \"vm_to_email_enabled\": -4231191,\n    \"voicemail_box\": {\n      \"additional_emails\": \"veniam quis\",\n      \"device_user_id\": 78470467,\n      \"id\": 97376636,\n      \"name\": \"minim id\"\n    },\n    \"voip_id\": \"eu consectetur cupidatat fugiat\"\n  },\n  \"request_id\": \"sunt\",\n  \"status\": \"nostrud tempor\"\n}"
						}
					]
				}
			],
			"id": "d0e7b53d-0bd1-4663-9319-7c26ca710b6a"
		},
		{
			"name": "deviceusers",
			"item": [
				{
					"name": "Get device user list",
					"id": "54883e80-2aba-4cd0-978a-cce098560be6",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/deviceusers",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"deviceusers"
							]
						},
						"description": "Get device user list"
					},
					"response": [
						{
							"id": "4f721222-391d-4b2e-80f2-f1fbfd7d7d58",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/deviceusers",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"deviceusers"
									]
								},
								"description": "Get device user list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 29257212,\n  \"data\": [\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"nulla occaecat officia nostrud\",\n          \"name\": \"cillum mollit dolor consectetur ea\"\n        },\n        \"created_at\": \"quis magna ut\",\n        \"enabled\": false,\n        \"id\": \"sunt non Excepteur et anim\",\n        \"master_account_id\": \"sed anim\",\n        \"name\": \"nisi ex do tempor\",\n        \"reseller_id\": 62667176,\n        \"sales_person\": {\n          \"first_name\": \"sed quis\",\n          \"id\": \"ea\",\n          \"last_name\": \"et nulla non\"\n        },\n        \"timezone\": \"labore\",\n        \"updated_at\": \"commodo\",\n        \"website\": \"pariatur aliquip\"\n      },\n      \"account_id\": 34405279,\n      \"add_to_directory\": true,\n      \"agent_status\": false,\n      \"busy_route\": \"ut in\",\n      \"busy_route_category\": \"eu Du\",\n      \"caller_id_external_number_id\": \"cupidatat in cillum\",\n      \"caller_id_internal_name\": \"ullamco et\",\n      \"caller_id_internal_number\": \"pariatur ipsum in eiusmod Excepteur\",\n      \"conference\": {\n        \"created_at\": \"ex mollit nostrud Lorem\",\n        \"device_user_id\": 14326673,\n        \"id\": -62940011,\n        \"id26\": \"id laborum mollit\",\n        \"join_deaf\": false,\n        \"join_muted\": true,\n        \"moderator_pin\": \"ni\",\n        \"moderators\": [\n          {\n            \"fugiat_c\": 99087222.81349441,\n            \"incididunt_6\": \"amet\"\n          },\n          {\n            \"laborum_3f3\": -68027583\n          }\n        ],\n        \"name\": \"ex sint qui\",\n        \"numbers\": \"proident culpa qui Lorem\",\n        \"pin\": 52479011,\n        \"updated_at\": \"cillum amet nulla\"\n      },\n      \"created_at\": \"pariatur deseru\",\n      \"devices\": [\n        {\n          \"additional_emails\": \"minim incididunt reprehenderit labore\",\n          \"device_template\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"manufacturer_id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"device_type\": \"adipisicing cupidatat\",\n          \"extension\": \"Ut\",\n          \"has_voicemail\": 42977528,\n          \"id26\": \"velit magna aliqua\",\n          \"keep_caller_id\": false,\n          \"mac_address\": \"aliqua elit Duis\",\n          \"manufacturer\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"manufacturer_model\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"name\": \"laboris non aute\",\n          \"number\": \"laboris et reprehenderit quis\",\n          \"require_keypress\": true,\n          \"restrict_caribbean\": \"ex occaecat\",\n          \"restrict_did_us\": \"aliquip mollit\",\n          \"restrict_international\": \"esse\",\n          \"restrict_toll_us\": \"consectetur nulla exercitation\",\n          \"restrict_tollfree_us\": \"reprehenderit\",\n          \"vm_to_email_enabled\": 65675795\n        },\n        {\n          \"additional_emails\": \"veni\",\n          \"device_template\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"manufacturer_id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"device_type\": \"labore sint Excepteur minim\",\n          \"extension\": \"amet n\",\n          \"has_voicemail\": 11200055,\n          \"id26\": \"sed adipisicing consequat cupi\",\n          \"keep_caller_id\": true,\n          \"mac_address\": \"culpa adipisicing veniam\",\n          \"manufacturer\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"manufacturer_model\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"name\": \"esse amet enim\",\n          \"number\": \"nisi Duis\",\n          \"require_keypress\": false,\n          \"restrict_caribbean\": \"sunt consequat ut adipisicing cupidatat\",\n          \"restrict_did_us\": \"fugiat aliqua et magna in\",\n          \"restrict_international\": \"dolore amet irure eu commodo\",\n          \"restrict_toll_us\": \"reprehenderit est Excepteur\",\n          \"restrict_tollfree_us\": \"non proident ani\",\n          \"vm_to_email_enabled\": -77802736\n        }\n      ],\n      \"dynamic_call_recording\": true,\n      \"e911_registration_user\": {\n        \"address_city\": \"i\",\n        \"address_street_1\": 28978616,\n        \"callback_number_id\": 8114510,\n        \"id\": -29869363,\n        \"id26\": \"in Ut dolore ut\",\n        \"name\": \"tempor dolore amet ut\"\n      },\n      \"email\": \"ut\",\n      \"first_name\": \"in et nisi ut id\",\n      \"fmfm\": true,\n      \"has_voicemail\": true,\n      \"id\": -85752921,\n      \"id26\": \"dolore proident\",\n      \"inbound_call_recording\": false,\n      \"last_name\": \"incididunt sed anim \",\n      \"mobile_app_access\": false,\n      \"mobile_presence\": false,\n      \"not_available_route_category\": \"consequat est\",\n      \"not_registered_number\": \"aliquip incididunt occaecat nulla\",\n      \"outbound_call_recording\": false,\n      \"phone_number\": {\n        \"call_routing_type\": \"esse magna\",\n        \"caller_id_prepend\": \"dolor al\",\n        \"created_at\": \"ut dolore\",\n        \"holiday1\": \"veniam ut\",\n        \"holiday2\": \"velit laboris irure incididunt\",\n        \"id\": -6702867,\n        \"id26\": \"nisi elit consequat\",\n        \"inbound_cnam_dip\": false,\n        \"main_number\": true,\n        \"main_number_last_updated\": \"mollit laborum ullamco est\",\n        \"outbound_caller_id\": \"non\",\n        \"phone_number\": \"Lorem adipi\",\n        \"routing_to1\": \"in in\",\n        \"routing_to2\": \"sunt occaecat ad\",\n        \"sms_routing\": 53000395,\n        \"status\": \"ea\",\n        \"t38_faxing\": false,\n        \"updated_at\": \"labore\"\n      },\n      \"prepend_caller_id\": \"quis in est do\",\n      \"reset_caller_id\": false,\n      \"seconds_to_ring\": 28669099,\n      \"timezone\": \"nulla qui officia\",\n      \"updated_at\": \"aliqua esse\",\n      \"vm_to_email_enabled\": true,\n      \"voicemail_box\": {\n        \"additional_emails\": \"fugiat non tempor\",\n        \"device_user_id\": -84719145,\n        \"id\": 24290218,\n        \"name\": \"cupidatat et in aute\"\n      },\n      \"webphone_e911_registration_id\": -9073423,\n      \"webphone_enabled\": false,\n      \"when_found_route_category\": \"deserunt ad sint L\"\n    },\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"et cillum laboris aliqua\",\n          \"name\": \"sunt occaecat anim consequat\"\n        },\n        \"created_at\": \"aliqua ad consectetur\",\n        \"enabled\": true,\n        \"id\": \"irure dolore\",\n        \"master_account_id\": \"deserunt non\",\n        \"name\": \"ullamco amet deserunt irure in\",\n        \"reseller_id\": 6515882,\n        \"sales_person\": {\n          \"first_name\": \"dolor dolore ut ullamco\",\n          \"id\": \"exercitation ut cupidatat\",\n          \"last_name\": \"esse\"\n        },\n        \"timezone\": \"sint occaecat dolore nisi\",\n        \"updated_at\": \"cillum ipsum adi\",\n        \"website\": \"do reprehenderit ut\"\n      },\n      \"account_id\": -93181979,\n      \"add_to_directory\": false,\n      \"agent_status\": false,\n      \"busy_route\": \"amet mollit\",\n      \"busy_route_category\": \"laborum amet Lorem ex\",\n      \"caller_id_external_number_id\": \"ad ullamco officia sint\",\n      \"caller_id_internal_name\": \"aliqua\",\n      \"caller_id_internal_number\": \"amet\",\n      \"conference\": {\n        \"created_at\": \"incididunt laborum veniam in\",\n        \"device_user_id\": -63759155,\n        \"id\": -56799375,\n        \"id26\": \"Duis\",\n        \"join_deaf\": true,\n        \"join_muted\": true,\n        \"moderator_pin\": \"nisi id\",\n        \"moderators\": [\n          {\n            \"qui81c\": false,\n            \"ut_30\": false\n          },\n          {\n            \"sint_7f\": false,\n            \"voluptate_4b_\": -31921502,\n            \"ex_3\": true\n          }\n        ],\n        \"name\": \"adipisicing est fugiat consequat occaecat\",\n        \"numbers\": \"nostrud\",\n        \"pin\": 23354618,\n        \"updated_at\": \"anim tempor Duis voluptate\"\n      },\n      \"created_at\": \"sint cupidatat\",\n      \"devices\": [\n        {\n          \"additional_emails\": \"dolor minim tempor\",\n          \"device_template\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"manufacturer_id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"device_type\": \"eu consequat mollit\",\n          \"extension\": \"sunt in\",\n          \"has_voicemail\": 82456679,\n          \"id26\": \"sunt magna labore aute\",\n          \"keep_caller_id\": false,\n          \"mac_address\": \"cupidatat ame\",\n          \"manufacturer\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"manufacturer_model\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"name\": \"in consectetur laboris dolor\",\n          \"number\": \"nulla\",\n          \"require_keypress\": true,\n          \"restrict_caribbean\": \"non\",\n          \"restrict_did_us\": \"irure\",\n          \"restrict_international\": \"esse aute exercit\",\n          \"restrict_toll_us\": \"magna\",\n          \"restrict_tollfree_us\": \"ad in\",\n          \"vm_to_email_enabled\": -23532378\n        },\n        {\n          \"additional_emails\": \"sint non\",\n          \"device_template\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"manufacturer_id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"device_type\": \"nulla incididunt culpa sint\",\n          \"extension\": \"eu ex exercitation culpa\",\n          \"has_voicemail\": -36612967,\n          \"id26\": \"adipisicing dolore Ut\",\n          \"keep_caller_id\": false,\n          \"mac_address\": \"nulla eiusmod\",\n          \"manufacturer\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"manufacturer_model\": {\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"title\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          },\n          \"name\": \"Excepteur non a\",\n          \"number\": \"dolor tempor Duis\",\n          \"require_keypress\": false,\n          \"restrict_caribbean\": \"qui enim occaecat\",\n          \"restrict_did_us\": \"cillum irure nisi eiusmod tempor\",\n          \"restrict_international\": \"reprehenderit occaecat do\",\n          \"restrict_toll_us\": \"aliqua elit Excepteur\",\n          \"restrict_tollfree_us\": \"eu esse\",\n          \"vm_to_email_enabled\": 80929375\n        }\n      ],\n      \"dynamic_call_recording\": false,\n      \"e911_registration_user\": {\n        \"address_city\": \"enim Excepteur in\",\n        \"address_street_1\": -51735620,\n        \"callback_number_id\": 98467068,\n        \"id\": -62424691,\n        \"id26\": \"mollit\",\n        \"name\": \"nisi eu ea\"\n      },\n      \"email\": \"in esse\",\n      \"first_name\": \"in magna\",\n      \"fmfm\": true,\n      \"has_voicemail\": true,\n      \"id\": -28994777,\n      \"id26\": \"laboris sunt minim et\",\n      \"inbound_call_recording\": true,\n      \"last_name\": \"aute o\",\n      \"mobile_app_access\": false,\n      \"mobile_presence\": true,\n      \"not_available_route_category\": \"exercitation in irure dolor\",\n      \"not_registered_number\": \"mollit pariatur ad commodo\",\n      \"outbound_call_recording\": false,\n      \"phone_number\": {\n        \"call_routing_type\": \"sint esse proident dolore dolor\",\n        \"caller_id_prepend\": \"dolor\",\n        \"created_at\": \"et adipisicing irure\",\n        \"holiday1\": \"sit aliqua amet officia magna\",\n        \"holiday2\": \"sit dolor elit nisi officia\",\n        \"id\": -92245054,\n        \"id26\": \"in commodo dolore\",\n        \"inbound_cnam_dip\": false,\n        \"main_number\": false,\n        \"main_number_last_updated\": \"consectetur proident\",\n        \"outbound_caller_id\": \"ut Duis q\",\n        \"phone_number\": \"ipsum aute aliqua deser\",\n        \"routing_to1\": \"adipisicing officia\",\n        \"routing_to2\": \"minim\",\n        \"sms_routing\": -48610325,\n        \"status\": \"cupidatat sed magna anim ex\",\n        \"t38_faxing\": true,\n        \"updated_at\": \"proident enim\"\n      },\n      \"prepend_caller_id\": \"aliqua\",\n      \"reset_caller_id\": false,\n      \"seconds_to_ring\": 27870441,\n      \"timezone\": \"aliqua\",\n      \"updated_at\": \"enim in commo\",\n      \"vm_to_email_enabled\": true,\n      \"voicemail_box\": {\n        \"additional_emails\": \"ullamco in pariatur irure cupidatat\",\n        \"device_user_id\": 49986307,\n        \"id\": 55637218,\n        \"name\": \"Excepteur eu\"\n      },\n      \"webphone_e911_registration_id\": 85052476,\n      \"webphone_enabled\": true,\n      \"when_found_route_category\": \"laborum sunt exercitation tempor sint\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 34691439,\n    \"page\": 32111195,\n    \"total_pages\": 44686650,\n    \"total_rows\": 48365648\n  },\n  \"request_id\": \"ut laboris dolor\",\n  \"status\": \"dolore sint ut aliqua\"\n}"
						}
					]
				},
				{
					"name": "Get device user details",
					"id": "e246a44b-4b3c-4c43-933d-b20af6f096f9",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/deviceusers/:device_user_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"deviceusers",
								":device_user_idorid26"
							],
							"variable": [
								{
									"key": "device_user_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of device user"
								}
							]
						},
						"description": "Get device user details"
					},
					"response": [
						{
							"id": "c437dce9-7011-434c-a113-40f0dbde9836",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/deviceusers/:device_user_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"deviceusers",
										":device_user_idorid26"
									],
									"variable": [
										{
											"key": "device_user_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of device user"
										}
									]
								},
								"description": "Get device user details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 68982278,\n  \"data\": {\n    \"account\": {\n      \"agent\": {\n        \"id\": \"sint consequat ea\",\n        \"name\": \"sunt ea tempor\"\n      },\n      \"created_at\": \"sunt velit\",\n      \"enabled\": true,\n      \"id\": \"sed dolor est Excepteur id\",\n      \"master_account_id\": \"ad in v\",\n      \"name\": \"laborum\",\n      \"reseller_id\": -2936224,\n      \"sales_person\": {\n        \"first_name\": \"esse\",\n        \"id\": \"cillum\",\n        \"last_name\": \"Duis labore\"\n      },\n      \"timezone\": \"ex minim\",\n      \"updated_at\": \"eu elit\",\n      \"website\": \"laborum eu ut enim\"\n    },\n    \"account_id\": -89484589,\n    \"add_to_directory\": true,\n    \"agent_status\": false,\n    \"busy_route\": \"culpa voluptate\",\n    \"busy_route_category\": \"eu in amet cupidatat quis\",\n    \"caller_id_external_number_id\": \"ea sunt deserunt\",\n    \"caller_id_internal_name\": \"consectetur anim\",\n    \"caller_id_internal_number\": \"qui dolore\",\n    \"conference\": {\n      \"created_at\": \"incididunt eu dolore ex\",\n      \"device_user_id\": 37053195,\n      \"id\": 85862607,\n      \"id26\": \"sint sed Excepteur et\",\n      \"join_deaf\": false,\n      \"join_muted\": true,\n      \"moderator_pin\": \"in magna labore\",\n      \"moderators\": [\n        {\n          \"sed_9\": -7563982.867465138,\n          \"in5\": \"in adi\"\n        },\n        {\n          \"ad91\": -52755132.0052829\n        }\n      ],\n      \"name\": \"occaecat labore sint\",\n      \"numbers\": \"irure\",\n      \"pin\": 83414234,\n      \"updated_at\": \"est pariatur aliquip non\"\n    },\n    \"created_at\": \"culpa\",\n    \"devices\": [\n      {\n        \"additional_emails\": \"quis irure i\",\n        \"device_template\": {\n          \"id\": -23103196,\n          \"manufacturer_id\": -48372684,\n          \"name\": \"sed mollit laboris proident\"\n        },\n        \"device_type\": \"tempor do\",\n        \"extension\": \"quis Excepteur\",\n        \"has_voicemail\": -30611460,\n        \"id26\": \"commodo\",\n        \"keep_caller_id\": true,\n        \"mac_address\": \"adipisicing non ad laboris\",\n        \"manufacturer\": {\n          \"id\": -28353416,\n          \"title\": \"mollit enim Ut eu\"\n        },\n        \"manufacturer_model\": {\n          \"id\": -50079602,\n          \"title\": \"in commodo\"\n        },\n        \"name\": \"dolor enim exercitation\",\n        \"number\": \"Ut\",\n        \"require_keypress\": false,\n        \"restrict_caribbean\": \"culpa officia deserunt labore\",\n        \"restrict_did_us\": \"fugiat anim\",\n        \"restrict_international\": \"exercitation occaecat\",\n        \"restrict_toll_us\": \"Excepteur cupida\",\n        \"restrict_tollfree_us\": \"laboris sit officia ea dolor\",\n        \"vm_to_email_enabled\": -57869948\n      },\n      {\n        \"additional_emails\": \"occaecat nulla elit proident eiusmod\",\n        \"device_template\": {\n          \"id\": 64918981,\n          \"manufacturer_id\": -7346368,\n          \"name\": \"aute aliquip officia ea\"\n        },\n        \"device_type\": \"labore occaecat magna proident\",\n        \"extension\": \"aliqua\",\n        \"has_voicemail\": -66038868,\n        \"id26\": \"v\",\n        \"keep_caller_id\": true,\n        \"mac_address\": \"sit do dolore\",\n        \"manufacturer\": {\n          \"id\": 62251642,\n          \"title\": \"ut esse\"\n        },\n        \"manufacturer_model\": {\n          \"id\": -19138048,\n          \"title\": \"ir\"\n        },\n        \"name\": \"cillum ipsum\",\n        \"number\": \"esse aliquip\",\n        \"require_keypress\": false,\n        \"restrict_caribbean\": \"labore ipsum reprehenderit\",\n        \"restrict_did_us\": \"do deserunt id\",\n        \"restrict_international\": \"ex esse dolore\",\n        \"restrict_toll_us\": \"fugiat\",\n        \"restrict_tollfree_us\": \"aliqua sunt Lorem\",\n        \"vm_to_email_enabled\": 37974418\n      }\n    ],\n    \"dynamic_call_recording\": true,\n    \"e911_registration_user\": {\n      \"address_city\": \"commodo deserunt dolore\",\n      \"address_street_1\": -33792298,\n      \"callback_number_id\": -41465288,\n      \"id\": 6387816,\n      \"id26\": \"qui\",\n      \"name\": \"consectetur deserunt Lorem eiusmod\"\n    },\n    \"email\": \"ex nostrud labo\",\n    \"first_name\": \"cupidatat nostrud dolore aliquip m\",\n    \"fmfm\": false,\n    \"has_voicemail\": false,\n    \"id\": 9658547,\n    \"id26\": \"cupidatat esse ut laborum\",\n    \"inbound_call_recording\": true,\n    \"last_name\": \"ut deserunt irure anim\",\n    \"mobile_app_access\": false,\n    \"mobile_presence\": false,\n    \"not_available_route_category\": \"dolor non\",\n    \"not_registered_number\": \"anim amet mollit occaecat\",\n    \"outbound_call_recording\": true,\n    \"phone_number\": {\n      \"call_routing_type\": \"aliquip esse offi\",\n      \"caller_id_prepend\": \"pariatur est dese\",\n      \"created_at\": \"amet\",\n      \"holiday1\": \"culpa\",\n      \"holiday2\": \"in reprehenderit officia\",\n      \"id\": 70435484,\n      \"id26\": \"cupidatat\",\n      \"inbound_cnam_dip\": false,\n      \"main_number\": true,\n      \"main_number_last_updated\": \"nulla\",\n      \"outbound_caller_id\": \"dolore ex consectetur\",\n      \"phone_number\": \"velit aliqua\",\n      \"routing_to1\": \"incididunt ut dolor e\",\n      \"routing_to2\": \"sit\",\n      \"sms_routing\": -23878165,\n      \"status\": \"deserunt laboris aliqua\",\n      \"t38_faxing\": false,\n      \"updated_at\": \"est fugiat\"\n    },\n    \"prepend_caller_id\": \"et in\",\n    \"reset_caller_id\": true,\n    \"seconds_to_ring\": -28874010,\n    \"timezone\": \"proident consequ\",\n    \"updated_at\": \"Excepteur elit cupidatat\",\n    \"vm_to_email_enabled\": false,\n    \"voicemail_box\": {\n      \"additional_emails\": \"laborum ex nostrud aute in\",\n      \"device_user_id\": 68250562,\n      \"id\": -23984970,\n      \"name\": \"minim ipsum qui fugiat ut\"\n    },\n    \"webphone_e911_registration_id\": -98330551,\n    \"webphone_enabled\": false,\n    \"when_found_route_category\": \"qui et\"\n  },\n  \"request_id\": \"nisi nostrud\",\n  \"status\": \"consectetur\"\n}"
						}
					]
				}
			],
			"id": "3e038712-afcb-4728-8f9b-14e9a5d763d4"
		},
		{
			"name": "disa",
			"item": [
				{
					"name": "Get disa list",
					"id": "c1e864be-a88e-4872-82f4-91d557b03d1e",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/disa",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"disa"
							]
						},
						"description": "Get disa list"
					},
					"response": [
						{
							"id": "490af888-6ec1-4d3d-8370-cc68ebbe30bf",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/disa",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"disa"
									]
								},
								"description": "Get disa list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -46979947,\n  \"data\": [\n    {\n      \"caller_id\": {\n        \"id\": 43039374,\n        \"phone_number\": \"in cillum ex\"\n      },\n      \"created_at\": \"aute id dolore ipsum\",\n      \"description\": \"ad officia\",\n      \"id\": -91768795,\n      \"id26\": \"ullamco nostrud\",\n      \"name\": \"pariatur\",\n      \"pin\": 10738974,\n      \"retries\": -16707753,\n      \"updated_at\": \"dolor velit elit ea ullamco\"\n    },\n    {\n      \"caller_id\": {\n        \"id\": -52097921,\n        \"phone_number\": \"laborum\"\n      },\n      \"created_at\": \"dolore sed commodo\",\n      \"description\": \"aute nisi esse cillum\",\n      \"id\": -66700132,\n      \"id26\": \"nostrud Excepteur\",\n      \"name\": \"aute adipisicing Excepteur d\",\n      \"pin\": 23789866,\n      \"retries\": 88196390,\n      \"updated_at\": \"ea Ut ips\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -65952178,\n    \"page\": 10001698,\n    \"total_pages\": -54354985,\n    \"total_rows\": -71713859\n  },\n  \"request_id\": \"dolore Duis sit cup\",\n  \"status\": \"aliquip consectetur et fugiat labore\"\n}"
						}
					]
				},
				{
					"name": "Get disa details",
					"id": "240eac4e-61e1-4572-9742-870cf9225aae",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/disa/:disa_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"disa",
								":disa_idorid26"
							],
							"variable": [
								{
									"key": "disa_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of disa"
								}
							]
						},
						"description": "Get disa details"
					},
					"response": [
						{
							"id": "b0043598-44b6-4cd8-9c4f-9808838f84d0",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/disa/:disa_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"disa",
										":disa_idorid26"
									],
									"variable": [
										{
											"key": "disa_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of disa"
										}
									]
								},
								"description": "Get disa details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -59673842,\n  \"data\": {\n    \"caller_id\": {\n      \"id\": -30661586,\n      \"phone_number\": \"ad\"\n    },\n    \"created_at\": \"ad laboris\",\n    \"description\": \"enim consequat dolor eiusmod\",\n    \"id\": 6622360,\n    \"id26\": \"in cupidatat deserunt\",\n    \"name\": \"esse ea ipsum\",\n    \"pin\": -74670561,\n    \"retries\": -55621467,\n    \"updated_at\": \"dolor mollit ipsum\"\n  },\n  \"request_id\": \"dolor\",\n  \"status\": \"pariatur quis magna in\"\n}"
						}
					]
				}
			],
			"id": "77a7338a-2849-4507-8edc-631e3d89b337"
		},
		{
			"name": "e911registrations",
			"item": [
				{
					"name": "Get e911 registration list",
					"id": "0d812c8c-6a8e-4b22-b4bc-6056a1627062",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/e911registrations",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"e911registrations"
							]
						},
						"description": "Get e911 registration list"
					},
					"response": [
						{
							"id": "80abc58f-504d-4d53-a28e-28e857c49558",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/e911registrations",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"e911registrations"
									]
								},
								"description": "Get e911 registration list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 21658838,\n  \"data\": [\n    {\n      \"account_id\": -86531135,\n      \"address_city\": \"fugiat ex sunt eiusmod\",\n      \"address_state\": \"irur\",\n      \"address_street_1\": \"quis anim dolore sit\",\n      \"address_street_2\": \"occaecat veniam in elit\",\n      \"address_zip\": \"nisi ut ea Ut\",\n      \"created_at\": \"minim sunt sit do magna\",\n      \"custom_provider\": -60643362,\n      \"devices\": [\n        {\n          \"device_type\": \"in\",\n          \"device_user_id\": -19556390,\n          \"e911_registration_id\": -37973409,\n          \"name\": \"commodo\",\n          \"user\": {\n            \"first_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"last_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          }\n        },\n        {\n          \"device_type\": \"sed in dolor\",\n          \"device_user_id\": 51083788,\n          \"e911_registration_id\": -286436,\n          \"name\": \"exercitation amet molli\",\n          \"user\": {\n            \"first_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"last_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          }\n        }\n      ],\n      \"emails\": [\n        {\n          \"e911_registration_id\": -78274521,\n          \"email\": \"laboris non irure\",\n          \"verified\": false\n        },\n        {\n          \"e911_registration_id\": 50768363,\n          \"email\": \"laborum labore amet dolore\",\n          \"verified\": false\n        }\n      ],\n      \"enabled\": -44333264,\n      \"id\": 88300250,\n      \"id26\": \"nisi in\",\n      \"latitude\": -10699268.686041921,\n      \"longitude\": -59569841.98701072,\n      \"name\": \"magna quis anim\",\n      \"phone\": {\n        \"id\": -45491760,\n        \"phone_number\": \"cillum quis Excepteur velit\"\n      },\n      \"site_id\": \"dolor proident Excepteur\",\n      \"updated_at\": \"voluptate elit velit ex\"\n    },\n    {\n      \"account_id\": -34660639,\n      \"address_city\": \"id\",\n      \"address_state\": \"fugiat ut\",\n      \"address_street_1\": \"ullamco dolor\",\n      \"address_street_2\": \"Ut velit id\",\n      \"address_zip\": \"ipsum occaecat sunt\",\n      \"created_at\": \"in aute anim ipsum\",\n      \"custom_provider\": 54963557,\n      \"devices\": [\n        {\n          \"device_type\": \"velit ea veniam\",\n          \"device_user_id\": 98795477,\n          \"e911_registration_id\": 3103523,\n          \"name\": \"sunt Dui\",\n          \"user\": {\n            \"first_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"last_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          }\n        },\n        {\n          \"device_type\": \"sunt\",\n          \"device_user_id\": 35210200,\n          \"e911_registration_id\": 3972258,\n          \"name\": \"laboris elit amet\",\n          \"user\": {\n            \"first_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"id\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            },\n            \"last_name\": {\n              \"value\": \"<Error: Too many levels of nesting to fake this schema>\"\n            }\n          }\n        }\n      ],\n      \"emails\": [\n        {\n          \"e911_registration_id\": -34202909,\n          \"email\": \"amet Duis\",\n          \"verified\": true\n        },\n        {\n          \"e911_registration_id\": 8817305,\n          \"email\": \"dolor incididunt nisi sint ad\",\n          \"verified\": false\n        }\n      ],\n      \"enabled\": 98656418,\n      \"id\": -22139952,\n      \"id26\": \"in amet proident sunt labore\",\n      \"latitude\": 72007856.23011461,\n      \"longitude\": -98738271.0824026,\n      \"name\": \"do\",\n      \"phone\": {\n        \"id\": 67393604,\n        \"phone_number\": \"cupidat\"\n      },\n      \"site_id\": \"est\",\n      \"updated_at\": \"sint\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -24240746,\n    \"page\": -72829373,\n    \"total_pages\": -80962999,\n    \"total_rows\": -68567224\n  },\n  \"request_id\": \"et cupidatat adipisicing sint\",\n  \"status\": \"adipisic\"\n}"
						}
					]
				},
				{
					"name": "Get e911 registration details",
					"id": "b4e23887-883d-4fc4-bcda-5e2d2fa8377b",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/e911registrations/:e911_registration_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"e911registrations",
								":e911_registration_idorid26"
							],
							"variable": [
								{
									"key": "e911_registration_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of e911 registration"
								}
							]
						},
						"description": "Get e911 registration details"
					},
					"response": [
						{
							"id": "2b57bc55-1a40-4c1a-96d5-58754462e601",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/e911registrations/:e911_registration_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"e911registrations",
										":e911_registration_idorid26"
									],
									"variable": [
										{
											"key": "e911_registration_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of e911 registration"
										}
									]
								},
								"description": "Get e911 registration details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -41999473,\n  \"data\": {\n    \"account_id\": -55463978,\n    \"address_city\": \"nostrud labore\",\n    \"address_state\": \"minim Excepteur ipsum\",\n    \"address_street_1\": \"ex voluptate culpa\",\n    \"address_street_2\": \"eu\",\n    \"address_zip\": \"aliqua anim Lorem Duis elit\",\n    \"created_at\": \"labore aliqua cillum Excepteur\",\n    \"custom_provider\": -11945326,\n    \"devices\": [\n      {\n        \"device_type\": \"in sint cillum\",\n        \"device_user_id\": -44752579,\n        \"e911_registration_id\": 11100429,\n        \"name\": \"in nisi\",\n        \"user\": {\n          \"first_name\": \"tempor commodo\",\n          \"id\": -28519854,\n          \"last_name\": \"anim reprehenderit\"\n        }\n      },\n      {\n        \"device_type\": \"ea deserunt\",\n        \"device_user_id\": -45843966,\n        \"e911_registration_id\": 66502777,\n        \"name\": \"aliqua\",\n        \"user\": {\n          \"first_name\": \"ut tempor id dolor\",\n          \"id\": 92548481,\n          \"last_name\": \"amet consectetur labore do\"\n        }\n      }\n    ],\n    \"emails\": [\n      {\n        \"e911_registration_id\": 52132543,\n        \"email\": \"dolor eu\",\n        \"verified\": true\n      },\n      {\n        \"e911_registration_id\": -79871747,\n        \"email\": \"do tempor\",\n        \"verified\": true\n      }\n    ],\n    \"enabled\": 27631730,\n    \"id\": -25612672,\n    \"id26\": \"nulla magna elit\",\n    \"latitude\": 65628995.79176581,\n    \"longitude\": -825661.0862980038,\n    \"name\": \"culpa consequat quis nis\",\n    \"phone\": {\n      \"id\": -69062749,\n      \"phone_number\": \"tempor exercitation\"\n    },\n    \"site_id\": \"pariatur occaecat\",\n    \"updated_at\": \"officia\"\n  },\n  \"request_id\": \"laborum adipisicing mollit venia\",\n  \"status\": \"Excepteur ad voluptate\"\n}"
						}
					]
				}
			],
			"id": "4619a3b2-f150-4cb1-921b-cd1fce2eb411"
		},
		{
			"name": "faxboxes",
			"item": [
				{
					"name": "Get fax box list",
					"id": "67858564-bb7a-4b2a-a475-2bfebcb332db",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/faxboxes",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"faxboxes"
							]
						},
						"description": "Get fax box list"
					},
					"response": [
						{
							"id": "2ba1c3e6-7f2d-4a16-883a-856836ac92e8",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/faxboxes",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"faxboxes"
									]
								},
								"description": "Get fax box list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -57543248,\n  \"data\": [\n    {\n      \"allowed_senders\": \"Lorem Duis\",\n      \"caller_id_name\": \"enim eiusmod\",\n      \"caller_id_number\": {\n        \"id\": 90713050,\n        \"phone_number\": \"aliquip\"\n      },\n      \"created_at\": \"tempo\",\n      \"device_user\": {\n        \"email\": \"nostrud ea consectetur ullamco\",\n        \"first_name\": \"labor\",\n        \"id\": -89707885,\n        \"last_name\": \"cillum non id voluptate consequat\"\n      },\n      \"domain_2\": \"adipisicing deserunt occaecat\",\n      \"email_address\": \"dolor nulla reprehenderit\",\n      \"fax_box_domain\": \"voluptate eiu\",\n      \"id\": -67165619,\n      \"id26\": \"cupidatat elit et ut laborum\",\n      \"name\": \"Duis minim sed quis\",\n      \"outbound_faxing\": true,\n      \"retries\": \"culpa cillum occaecat\",\n      \"sent_receipts\": false,\n      \"timezone\": \"labore in laborum eu cillum\",\n      \"updated_at\": \"veniam exercitation\"\n    },\n    {\n      \"allowed_senders\": \"nisi est\",\n      \"caller_id_name\": \"eu dolore amet minim\",\n      \"caller_id_number\": {\n        \"id\": -14132665,\n        \"phone_number\": \"aute exercitation ut laboris\"\n      },\n      \"created_at\": \"pariatur\",\n      \"device_user\": {\n        \"email\": \"elit sunt Ut\",\n        \"first_name\": \"ex sit qui do\",\n        \"id\": -49280135,\n        \"last_name\": \"pariatur officia dolor nostrud occaecat\"\n      },\n      \"domain_2\": \"\",\n      \"email_address\": \"commodo culpa est\",\n      \"fax_box_domain\": \"Ut ipsum occaecat\",\n      \"id\": 18449858,\n      \"id26\": \"cillum esse sint reprehenderit\",\n      \"name\": \"Excepteur veniam\",\n      \"outbound_faxing\": false,\n      \"retries\": \"occaecat commodo\",\n      \"sent_receipts\": false,\n      \"timezone\": \"ut dolore aut\",\n      \"updated_at\": \"laboris deserunt sit aute\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -23611425,\n    \"page\": 51787764,\n    \"total_pages\": -61770887,\n    \"total_rows\": -49814455\n  },\n  \"request_id\": \"dolore sunt in sint\",\n  \"status\": \"laborum fugiat amet eiusmod\"\n}"
						}
					]
				},
				{
					"name": "Get fax box details",
					"id": "043a0adf-3b8a-4380-b10b-f6edc797cbc2",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/faxboxes/:fax_box_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"faxboxes",
								":fax_box_idorid26"
							],
							"variable": [
								{
									"key": "fax_box_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of fax box"
								}
							]
						},
						"description": "Get fax  box details"
					},
					"response": [
						{
							"id": "22b2f405-bd6c-44a7-80bf-897fab259145",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/faxboxes/:fax_box_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"faxboxes",
										":fax_box_idorid26"
									],
									"variable": [
										{
											"key": "fax_box_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of fax box"
										}
									]
								},
								"description": "Get fax  box details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -62839882,\n  \"data\": {\n    \"allowed_senders\": \"Duis dolore\",\n    \"caller_id_name\": \"laborum\",\n    \"caller_id_number\": {\n      \"id\": 62351275,\n      \"phone_number\": \"et cillum occaecat magna\"\n    },\n    \"created_at\": \"occaecat\",\n    \"device_user\": {\n      \"email\": \"ex Excepteur ullamco\",\n      \"first_name\": \"Duis mollit minim in\",\n      \"id\": 63988649,\n      \"last_name\": \"occaecat exercitation\"\n    },\n    \"domain_2\": \"Duis dolor\",\n    \"email_address\": \"elit consectetur ut\",\n    \"fax_box_domain\": \"sit in\",\n    \"id\": -10848430,\n    \"id26\": \"ea Duis aliqua et\",\n    \"name\": \"dolore voluptate ex\",\n    \"outbound_faxing\": false,\n    \"retries\": \"a\",\n    \"sent_receipts\": false,\n    \"timezone\": \"co\",\n    \"updated_at\": \"sint ipsum ex laboris nisi\"\n  },\n  \"request_id\": \"nulla Ut voluptate nostrud\",\n  \"status\": \"commodo\"\n}"
						}
					]
				}
			],
			"id": "011cc23c-c5ee-4546-982d-ccf9443e9aeb"
		},
		{
			"name": "groups",
			"item": [
				{
					"name": "Get group list",
					"id": "ebb98955-506c-4e29-9044-ce3382481253",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/groups",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"groups"
							]
						},
						"description": "Get group list"
					},
					"response": [
						{
							"id": "5c606edd-ff34-4911-bf41-44fd6e2ce8fb",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/groups",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"groups"
									]
								},
								"description": "Get group list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -87301037,\n  \"data\": [\n    {\n      \"account_id\": -29090140,\n      \"after_group_forward_call\": {\n        \"exercitation_4\": 49442682.992617816\n      },\n      \"callflow_voip_id\": \"dolore ut\",\n      \"created_at\": \"sed in\",\n      \"group_endpoints\": [\n        {\n          \"labore_47\": -17391978.54074712,\n          \"adf5\": -34348201\n        },\n        {\n          \"Excepteur59\": \"officia reprehenderit\"\n        }\n      ],\n      \"id\": 15018259,\n      \"id26\": \"dolor u\",\n      \"inbound_call_recording\": false,\n      \"media\": {\n        \"category\": \"culpa id ut voluptate\",\n        \"id\": 135373,\n        \"name\": \"sit nostrud culpa aliquip\"\n      },\n      \"media_id\": -35644961,\n      \"name\": \"Duis consectetur non officia\",\n      \"prepend_to_caller_id_name\": \"dolor ipsum minim labore\",\n      \"repeat\": -3099098,\n      \"reset_caller_id\": false,\n      \"ring_all_sequentially\": \"aute officia ad\",\n      \"seconds_to_ring\": -75789072,\n      \"selector\": \"voluptate amet\",\n      \"should_play_media\": false,\n      \"updated_at\": \"commodo laborum veniam \",\n      \"voip_id\": \"ullamco officia irure Ut anim\"\n    },\n    {\n      \"account_id\": 68389458,\n      \"after_group_forward_call\": {\n        \"quis_c7\": false\n      },\n      \"callflow_voip_id\": \"occaecat deserunt dolor quis\",\n      \"created_at\": \"ut\",\n      \"group_endpoints\": [\n        {\n          \"qui_1\": false\n        },\n        {\n          \"consectetur_16e\": -54031774.11385301,\n          \"culpa_e3d\": -36429804.3729538,\n          \"Excepteur5\": false\n        }\n      ],\n      \"id\": -35615515,\n      \"id26\": \"nisi commodo\",\n      \"inbound_call_recording\": false,\n      \"media\": {\n        \"category\": \"nisi in incididunt dolor\",\n        \"id\": -19519906,\n        \"name\": \"eiusmod Duis aliqua reprehenderit\"\n      },\n      \"media_id\": 3058379,\n      \"name\": \"Ut ut\",\n      \"prepend_to_caller_id_name\": \"culpa et exercitation do\",\n      \"repeat\": 86730394,\n      \"reset_caller_id\": false,\n      \"ring_all_sequentially\": \"nisi dolore velit minim pariatur\",\n      \"seconds_to_ring\": -13534189,\n      \"selector\": \"aute\",\n      \"should_play_media\": true,\n      \"updated_at\": \"amet veniam\",\n      \"voip_id\": \"f\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -64258284,\n    \"page\": -16670747,\n    \"total_pages\": 90075818,\n    \"total_rows\": -26798921\n  },\n  \"request_id\": \"elit \",\n  \"status\": \"est magna\"\n}"
						}
					]
				},
				{
					"name": "Get group details",
					"id": "2946a76a-a582-48e9-acf7-5ee1433955e1",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/groups/:group_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"groups",
								":group_idorid26"
							],
							"variable": [
								{
									"key": "group_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of group"
								}
							]
						},
						"description": "Get group details"
					},
					"response": [
						{
							"id": "a363cd60-1f38-4c72-b820-0f817094e169",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/groups/:group_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"groups",
										":group_idorid26"
									],
									"variable": [
										{
											"key": "group_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of group"
										}
									]
								},
								"description": "Get group details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 5900745,\n  \"data\": {\n    \"account_id\": -3022749,\n    \"after_group_forward_call\": {\n      \"laboris_ca3\": \"et pariatur\"\n    },\n    \"callflow_voip_id\": \"enim dolor id eu\",\n    \"created_at\": \"mi\",\n    \"group_endpoints\": [\n      {\n        \"id_1e\": \"n\"\n      },\n      {\n        \"exercitation_20\": false\n      }\n    ],\n    \"id\": 1773,\n    \"id26\": \"ad est velit\",\n    \"inbound_call_recording\": false,\n    \"media\": {\n      \"category\": \"laboris commodo sed\",\n      \"id\": -88311014,\n      \"name\": \"sed veniam magna ipsum\"\n    },\n    \"media_id\": -63654193,\n    \"name\": \"officia in cillum\",\n    \"prepend_to_caller_id_name\": \"reprehenderit officia\",\n    \"repeat\": 33802509,\n    \"reset_caller_id\": true,\n    \"ring_all_sequentially\": \"consectetur\",\n    \"seconds_to_ring\": -25424402,\n    \"selector\": \"sed ex Excep\",\n    \"should_play_media\": false,\n    \"updated_at\": \"consequat in non\",\n    \"voip_id\": \"est ad\"\n  },\n  \"request_id\": \"consectetur occaecat\",\n  \"status\": \"exercitation tempor\"\n}"
						}
					]
				}
			],
			"id": "8342aba1-f5c6-45f8-ae88-f176c36b06c6"
		},
		{
			"name": "holidayroutingsettings",
			"item": [
				{
					"name": "Get holiday routing list",
					"id": "fc830e53-1ecc-4a63-97a5-b49ec2860b48",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/holidayroutingsettings",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"holidayroutingsettings"
							]
						},
						"description": "Get holiday routing list"
					},
					"response": [
						{
							"id": "715bcaf1-f0bb-4f58-ad3c-df2186389c66",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/holidayroutingsettings",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"holidayroutingsettings"
									]
								},
								"description": "Get holiday routing list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -48535775,\n  \"data\": [\n    {\n      \"activate\": true,\n      \"all_day\": true,\n      \"created_at\": \"nulla nostrud cillum\",\n      \"enabled\": true,\n      \"id\": 71643239,\n      \"id26\": \"dolor id ex nulla\",\n      \"monthly_day\": \"quis sit in\",\n      \"monthly_ordinal\": \"dolore dolor aute mollit\",\n      \"monthly_type\": \"adipisicing ullamco dolor\",\n      \"monthly_weekday\": \"officia mollit commodo\",\n      \"name\": \"culpa laborum consectetur in mollit\",\n      \"repeats\": \"elit qui Lorem sunt ut\",\n      \"site_id\": -39480588,\n      \"start_date\": \"aliquip ullamco dolore deserunt\",\n      \"summary\": \"magna exercitation\",\n      \"time_begin\": \"exercitation officia deserunt nulla\",\n      \"time_end\": \"et voluptate\",\n      \"type\": \"sint non\",\n      \"updated_at\": \"ut consectetur\",\n      \"weekly_weekday\": \"aliq\",\n      \"yearly_day\": \"non in\",\n      \"yearly_month\": \"nostrud incididunt tempor\",\n      \"yearly_ordinal\": \"sed ex dolor\",\n      \"yearly_type\": \"Excepteur mollit eu est\",\n      \"yearly_weekday\": \"enim\"\n    },\n    {\n      \"activate\": true,\n      \"all_day\": false,\n      \"created_at\": \"ea nostrud velit\",\n      \"enabled\": false,\n      \"id\": 81974866,\n      \"id26\": \"deserunt magna\",\n      \"monthly_day\": \"anim minim voluptate\",\n      \"monthly_ordinal\": \"eu aliquip proident enim dolor\",\n      \"monthly_type\": \"nostrud fugiat consectetur minim\",\n      \"monthly_weekday\": \"consequat ex\",\n      \"name\": \"ex minim laborum reprehenderit\",\n      \"repeats\": \"irure ipsu\",\n      \"site_id\": 42793654,\n      \"start_date\": \"in\",\n      \"summary\": \"occaecat tempor sunt in veniam\",\n      \"time_begin\": \"dolore iru\",\n      \"time_end\": \"in adipisicing laboris culpa\",\n      \"type\": \"laborum Du\",\n      \"updated_at\": \"mollit consequat ea in\",\n      \"weekly_weekday\": \"aute Except\",\n      \"yearly_day\": \"adipisicing velit dolore ex\",\n      \"yearly_month\": \"do officia\",\n      \"yearly_ordinal\": \"eiusmod dolore qui dolor\",\n      \"yearly_type\": \"sed nisi id mollit amet\",\n      \"yearly_weekday\": \"enim ut\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -38783482,\n    \"page\": 88965231,\n    \"total_pages\": 29621334,\n    \"total_rows\": -93098618\n  },\n  \"request_id\": \"nisi ad culpa voluptate\",\n  \"status\": \"labore\"\n}"
						}
					]
				},
				{
					"name": "Get holiday routing details",
					"id": "97fa5936-6a31-4c10-868a-90d9bf1e64ef",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/holidayroutingsettings/:holiday_routing_setting_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"holidayroutingsettings",
								":holiday_routing_setting_idorid26"
							],
							"variable": [
								{
									"key": "holiday_routing_setting_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of HolidayRoutingSetting"
								}
							]
						},
						"description": "Get holiday routing details"
					},
					"response": [
						{
							"id": "ac9052b6-008c-4cac-86d3-bd0d1d141c78",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/holidayroutingsettings/:holiday_routing_setting_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"holidayroutingsettings",
										":holiday_routing_setting_idorid26"
									],
									"variable": [
										{
											"key": "holiday_routing_setting_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of HolidayRoutingSetting"
										}
									]
								},
								"description": "Get holiday routing details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 91739557,\n  \"data\": {\n    \"activate\": true,\n    \"all_day\": true,\n    \"created_at\": \"officia tempor\",\n    \"enabled\": false,\n    \"id\": 73722476,\n    \"id26\": \"id ex dolore\",\n    \"monthly_day\": \"ad\",\n    \"monthly_ordinal\": \"in voluptate qui dolore aute\",\n    \"monthly_type\": \"cons\",\n    \"monthly_weekday\": \"ea nisi par\",\n    \"name\": \"cupidatat\",\n    \"repeats\": \"sint laboris aliquip Duis\",\n    \"site_id\": 58354405,\n    \"start_date\": \"cupidatat reprehenderit ipsum laborum\",\n    \"summary\": \"velit sint veniam\",\n    \"time_begin\": \"ipsum reprehenderit\",\n    \"time_end\": \"anim aute commodo in\",\n    \"type\": \"amet deserunt labore\",\n    \"updated_at\": \"elit pariatur cupidatat ea\",\n    \"weekly_weekday\": \"elit labore non esse\",\n    \"yearly_day\": \"sit tempor\",\n    \"yearly_month\": \"nisi\",\n    \"yearly_ordinal\": \"minim occaecat sed labore\",\n    \"yearly_type\": \"culpa enim\",\n    \"yearly_weekday\": \"in minim\"\n  },\n  \"request_id\": \"tempor non\",\n  \"status\": \"dolor aliquip fugiat amet\"\n}"
						}
					]
				}
			],
			"id": "bd7356de-881f-4937-a46f-8ea0420c22fa"
		},
		{
			"name": "mediafiles",
			"item": [
				{
					"name": "Get media file list",
					"id": "197f2bc7-f24e-4ac8-8a02-2b4b70910cdd",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/mediafiles",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"mediafiles"
							]
						},
						"description": "Get media file list"
					},
					"response": [
						{
							"id": "4bf15c0b-18fc-4ef0-8ee6-b798ceb32b31",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/mediafiles",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"mediafiles"
									]
								},
								"description": "Get media file list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -87839523,\n  \"data\": [\n    {\n      \"category\": \"irure\",\n      \"created_at\": \"consectetur incididunt\",\n      \"description\": \"deserunt exercitation in\",\n      \"id\": 42659649,\n      \"id26\": \"est sint ipsum laborum\",\n      \"name\": \"exercitation\",\n      \"updated_at\": \"deserunt minim \"\n    },\n    {\n      \"category\": \"consequat reprehenderit\",\n      \"created_at\": \"labore magna fugiat Lorem dolore\",\n      \"description\": \"do ut sunt\",\n      \"id\": -83666105,\n      \"id26\": \"\",\n      \"name\": \"culpa nulla ad amet\",\n      \"updated_at\": \"nisi sint tempor\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -40002678,\n    \"page\": -18052000,\n    \"total_pages\": -71826739,\n    \"total_rows\": -35844458\n  },\n  \"request_id\": \"exercitation\",\n  \"status\": \"adipisicing eiusmod\"\n}"
						}
					]
				},
				{
					"name": "Get media file details",
					"id": "41b4ba2a-81cc-4f1a-a82e-d5ccc6cc4a29",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/mediafiles/:media_file_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"mediafiles",
								":media_file_idorid26"
							],
							"variable": [
								{
									"key": "media_file_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of MediaFile"
								}
							]
						},
						"description": "Get media file details"
					},
					"response": [
						{
							"id": "68e76e69-7f41-4148-9c0f-5f7d8c0e69c5",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/mediafiles/:media_file_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"mediafiles",
										":media_file_idorid26"
									],
									"variable": [
										{
											"key": "media_file_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of MediaFile"
										}
									]
								},
								"description": "Get media file details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -54877936,\n  \"data\": {\n    \"category\": \"dolor adipisi\",\n    \"created_at\": \"sit fugiat ad\",\n    \"description\": \"sint laborum officia cupidatat\",\n    \"id\": -51497346,\n    \"id26\": \"dolor aute in\",\n    \"name\": \"magna ullamco cupidatat eu\",\n    \"updated_at\": \"sed dolore nisi\"\n  },\n  \"request_id\": \"Excepteur\",\n  \"status\": \"qui nulla\"\n}"
						}
					]
				}
			],
			"id": "8ef44525-b60b-4dcd-81b7-c10465d295bf"
		},
		{
			"name": "menus",
			"item": [
				{
					"name": "Get menu list",
					"id": "b1f4266c-f322-4795-b1ae-369beb33f79c",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/menus",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"menus"
							]
						},
						"description": "Get menu list"
					},
					"response": [
						{
							"id": "7c652a08-82d3-4ec9-8995-6751feccffc1",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/menus",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"menus"
									]
								},
								"description": "Get menu list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -88400008,\n  \"data\": [\n    {\n      \"allow_extension\": false,\n      \"allow_record_from_outside\": true,\n      \"created_at\": \"officia laborum\",\n      \"id\": -58242933,\n      \"id26\": \"elit Lorem consequat\",\n      \"media\": {\n        \"category\": \"aliquip Duis enim adipisicing\",\n        \"id\": -7782031,\n        \"name\": \"laborum ullamco aliqua\"\n      },\n      \"media_id\": 27873174,\n      \"media_type\": \"incididunt do consectetur\",\n      \"name\": \"in esse officia consecte\",\n      \"record_pin\": \"ea dolor quis enim\",\n      \"retries\": \"voluptate culpa Excepteur ad\",\n      \"route_0\": -63753179,\n      \"route_0_category\": \"ut commodo aute est\",\n      \"route_1\": -49334387,\n      \"route_1_category\": \"nostrud ipsum magna\",\n      \"route_2\": -27048359,\n      \"route_2_category\": \"id\",\n      \"route_3\": -4314146,\n      \"route_3_category\": \"et esse sit dolor\",\n      \"route_4\": 97195028,\n      \"route_4_category\": \"dolore aute\",\n      \"route_5\": -36380744,\n      \"route_5_category\": \"reprehenderit\",\n      \"route_6\": 94428792,\n      \"route_6_category\": \"aliquip do\",\n      \"route_7\": -8826540,\n      \"route_7_category\": \"incididunt commodo aliq\",\n      \"route_8\": -39594047,\n      \"route_8_category\": \"esse dolor Excepteur ad\",\n      \"route_9\": -79875608,\n      \"route_9_category\": \"elit\",\n      \"route_ast\": -59945326,\n      \"route_ast_category\": \"ea cupidat\",\n      \"route_timeout\": -87334209,\n      \"route_timeout_category\": \"exercitation consequat\",\n      \"suppress_media\": false,\n      \"timeout\": \"id magna mollit dolor nulla\",\n      \"updated_at\": \"Ut et\"\n    },\n    {\n      \"allow_extension\": true,\n      \"allow_record_from_outside\": false,\n      \"created_at\": \"ex\",\n      \"id\": 9690739,\n      \"id26\": \"adipisicing consequat dolore laboris\",\n      \"media\": {\n        \"category\": \"consectetur\",\n        \"id\": 96080153,\n        \"name\": \"aliqua\"\n      },\n      \"media_id\": -1402965,\n      \"media_type\": \"mollit adipisicing eu in\",\n      \"name\": \"id minim in sint pariatur\",\n      \"record_pin\": \"nostrud in irure mollit eiusmod\",\n      \"retries\": \"velit\",\n      \"route_0\": -62051702,\n      \"route_0_category\": \"reprehenderit nostrud dolor occaecat\",\n      \"route_1\": -26042666,\n      \"route_1_category\": \"nostrud ullamco mollit Excepteur\",\n      \"route_2\": -49302372,\n      \"route_2_category\": \"quis minim\",\n      \"route_3\": -51068659,\n      \"route_3_category\": \"culpa sit\",\n      \"route_4\": -38800060,\n      \"route_4_category\": \"in non nostrud\",\n      \"route_5\": -24500013,\n      \"route_5_category\": \"non consec\",\n      \"route_6\": -34897393,\n      \"route_6_category\": \"quis magna in\",\n      \"route_7\": -18108487,\n      \"route_7_category\": \"Lorem culpa eu consectetur\",\n      \"route_8\": -45965119,\n      \"route_8_category\": \"dolore pariatur\",\n      \"route_9\": 23074241,\n      \"route_9_category\": \"dolore quis non\",\n      \"route_ast\": 56622835,\n      \"route_ast_category\": \"sit\",\n      \"route_timeout\": 48851846,\n      \"route_timeout_category\": \"aliquip aliqua eu veniam nostrud\",\n      \"suppress_media\": false,\n      \"timeout\": \"ea ut magna tempor ipsum\",\n      \"updated_at\": \"dolore in labore cupidatat\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -57401179,\n    \"page\": -61864451,\n    \"total_pages\": 60697295,\n    \"total_rows\": -41625870\n  },\n  \"request_id\": \"cillum ut irure magna\",\n  \"status\": \"i\"\n}"
						}
					]
				},
				{
					"name": "Get menu details",
					"id": "efa24617-a61f-47c2-b63d-137e5b6e5b15",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/menus/:menu_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"menus",
								":menu_idorid26"
							],
							"variable": [
								{
									"key": "menu_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of Menu"
								}
							]
						},
						"description": "Get menu details"
					},
					"response": [
						{
							"id": "51eed3c6-e8d3-4fa8-ba63-46745bbfc660",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/menus/:menu_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"menus",
										":menu_idorid26"
									],
									"variable": [
										{
											"key": "menu_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of Menu"
										}
									]
								},
								"description": "Get menu details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -74398190,\n  \"data\": {\n    \"allow_extension\": false,\n    \"allow_record_from_outside\": false,\n    \"created_at\": \"et esse\",\n    \"id\": 84772494,\n    \"id26\": \"cillum cupidatat\",\n    \"media\": {\n      \"category\": \"esse occaecat eu\",\n      \"id\": -35973026,\n      \"name\": \"consequat\"\n    },\n    \"media_id\": 46497266,\n    \"media_type\": \"ea sunt aute eu laborum\",\n    \"name\": \"deserunt fugiat in laborum\",\n    \"record_pin\": \"in id reprehenderit\",\n    \"retries\": \"nulla in\",\n    \"route_0\": -14456021,\n    \"route_0_category\": \"do veniam non\",\n    \"route_1\": 29363206,\n    \"route_1_category\": \"in dolore in dolor\",\n    \"route_2\": 99507662,\n    \"route_2_category\": \"mollit id quis\",\n    \"route_3\": -95302247,\n    \"route_3_category\": \"enim aliqua fugiat commodo\",\n    \"route_4\": 84697059,\n    \"route_4_category\": \"quis enim\",\n    \"route_5\": -18500018,\n    \"route_5_category\": \"fugiat quis commodo incididunt\",\n    \"route_6\": 98855800,\n    \"route_6_category\": \"do ad eu reprehenderit fugiat\",\n    \"route_7\": -99237887,\n    \"route_7_category\": \"aute minim et adipisicing\",\n    \"route_8\": -12361591,\n    \"route_8_category\": \"o\",\n    \"route_9\": -50228948,\n    \"route_9_category\": \"incididunt ullamco proident l\",\n    \"route_ast\": 61548676,\n    \"route_ast_category\": \"fugiat\",\n    \"route_timeout\": -73338720,\n    \"route_timeout_category\": \"ad esse proide\",\n    \"suppress_media\": false,\n    \"timeout\": \"sint Lorem non tempor\",\n    \"updated_at\": \"minim ex Ut ut dolor\"\n  },\n  \"request_id\": \"sed Duis ex ea\",\n  \"status\": \"amet deserunt\"\n}"
						}
					]
				}
			],
			"id": "422749c9-a380-4700-9e41-0ea4063e7cbd"
		},
		{
			"name": "pbxconnectors",
			"item": [
				{
					"name": "Get PBX connector list",
					"id": "1184c95f-df2d-4731-a4a4-ff47db1d8653",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/pbxconnectors",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"pbxconnectors"
							]
						},
						"description": "Get PBX connector list"
					},
					"response": [
						{
							"id": "96064ab9-d352-46dd-851b-3465fa22f5c6",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/pbxconnectors",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"pbxconnectors"
									]
								},
								"description": "Get PBX connector list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 94814944,\n  \"data\": [\n    {\n      \"caller_id_number\": {\n        \"id\": -11025503,\n        \"phone_number\": \"amet elit ut\"\n      },\n      \"caller_id_number_other\": \"sint mollit cupidatat\",\n      \"caller_id_pass_thru\": false,\n      \"created_at\": \"officia ut proident\",\n      \"dynamic_call_recording\": false,\n      \"e911_caller_id_pass_thru\": false,\n      \"emergency_caller_id_number\": {\n        \"address_city\": \"dolore veniam in consectetur eiusmod\",\n        \"address_state\": \"ipsum anim tempor Duis est\",\n        \"address_street_1\": \"qui tempor eu in\",\n        \"id\": -78408432\n      },\n      \"id\": 32054615,\n      \"id26\": \"aute\",\n      \"inbound_call_recording\": false,\n      \"name\": \"proident sint\",\n      \"outbound_call_recording\": false,\n      \"pbx_manufacturer\": {\n        \"id\": 39409555,\n        \"title\": \"minim ip\"\n      },\n      \"pbx_manufacturer_other\": \"labore esse\",\n      \"pbx_model\": {\n        \"id\": -39049849,\n        \"title\": \"magna veniam exercitation\"\n      },\n      \"pbx_model_other\": \"cillum est sit\",\n      \"pbx_type\": \"et\",\n      \"site\": {\n        \"id\": -17547843,\n        \"name\": \"dolore\"\n      },\n      \"updated_at\": \"exercitation cupidatat ullamco\"\n    },\n    {\n      \"caller_id_number\": {\n        \"id\": -86808252,\n        \"phone_number\": \"velit magna ipsum incididunt\"\n      },\n      \"caller_id_number_other\": \"pariatur dolore magna ut ipsum\",\n      \"caller_id_pass_thru\": true,\n      \"created_at\": \"magna eiusmod quis\",\n      \"dynamic_call_recording\": true,\n      \"e911_caller_id_pass_thru\": false,\n      \"emergency_caller_id_number\": {\n        \"address_city\": \"labore irure\",\n        \"address_state\": \"conseq\",\n        \"address_street_1\": \"ut non consectetur nulla\",\n        \"id\": -95265105\n      },\n      \"id\": -97922424,\n      \"id26\": \"adipisicing sit ad non\",\n      \"inbound_call_recording\": false,\n      \"name\": \"exercitation velit\",\n      \"outbound_call_recording\": true,\n      \"pbx_manufacturer\": {\n        \"id\": -33972331,\n        \"title\": \"minim mollit\"\n      },\n      \"pbx_manufacturer_other\": \"cupidatat ea nulla id nisi\",\n      \"pbx_model\": {\n        \"id\": 89115433,\n        \"title\": \"dolor eu\"\n      },\n      \"pbx_model_other\": \"enim amet\",\n      \"pbx_type\": \"aliquip dolor sit\",\n      \"site\": {\n        \"id\": 46919428,\n        \"name\": \"eiusmod labore aliquip laborum incididunt\"\n      },\n      \"updated_at\": \"quis amet\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 24524231,\n    \"page\": 3016881,\n    \"total_pages\": 65946115,\n    \"total_rows\": -1914121\n  },\n  \"request_id\": \"qui sint est ut\",\n  \"status\": \"ut irure\"\n}"
						}
					]
				},
				{
					"name": "Get PBX connector details",
					"id": "5326c2c7-a9f8-4de0-9ed0-7f34170fd4c9",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/pbxconnectors/:pbx_connector_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"pbxconnectors",
								":pbx_connector_idorid26"
							],
							"variable": [
								{
									"key": "pbx_connector_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of pbx connector"
								}
							]
						},
						"description": "Get PBX connector details"
					},
					"response": [
						{
							"id": "6dc681bc-5462-48e6-a623-e71e54661baa",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/pbxconnectors/:pbx_connector_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"pbxconnectors",
										":pbx_connector_idorid26"
									],
									"variable": [
										{
											"key": "pbx_connector_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of pbx connector"
										}
									]
								},
								"description": "Get PBX connector details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 93546711,\n  \"data\": {\n    \"caller_id_number\": {\n      \"id\": -78825671,\n      \"phone_number\": \"et sed\"\n    },\n    \"caller_id_number_other\": \"exercitation nos\",\n    \"caller_id_pass_thru\": true,\n    \"created_at\": \"adipisicing in tempor\",\n    \"dynamic_call_recording\": true,\n    \"e911_caller_id_pass_thru\": false,\n    \"emergency_caller_id_number\": {\n      \"address_city\": \"magna\",\n      \"address_state\": \"consequat Ut reprehenderit anim nisi\",\n      \"address_street_1\": \"labore aliqua fugiat q\",\n      \"id\": -7360821\n    },\n    \"id\": -39607515,\n    \"id26\": \"ut in\",\n    \"inbound_call_recording\": true,\n    \"name\": \"Lorem enim minim ut i\",\n    \"outbound_call_recording\": false,\n    \"pbx_manufacturer\": {\n      \"id\": 97681351,\n      \"title\": \"amet veniam nulla\"\n    },\n    \"pbx_manufacturer_other\": \"non Duis aliquip\",\n    \"pbx_model\": {\n      \"id\": -87594066,\n      \"title\": \"ad commodo amet in\"\n    },\n    \"pbx_model_other\": \"elit Excepteur labore ut non\",\n    \"pbx_type\": \"reprehenderit culpa\",\n    \"site\": {\n      \"id\": 77698227,\n      \"name\": \"sint Duis adipisicing consectetur sed\"\n    },\n    \"updated_at\": \"officia Duis in quis\"\n  },\n  \"request_id\": \"dolore\",\n  \"status\": \"ea eu ad adipisicing sunt\"\n}"
						}
					]
				}
			],
			"id": "87b48c4e-f2f0-47bd-93e4-1c366aa8624f"
		},
		{
			"name": "phonenumbers",
			"item": [
				{
					"name": "Get phone number list",
					"id": "53291879-c478-4215-b241-5cfd1f95e27d",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/phonenumbers",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"phonenumbers"
							]
						},
						"description": "Get phone number list"
					},
					"response": [
						{
							"id": "7d0a1abb-f392-4fc8-aeeb-fc2de8e3647b",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/phonenumbers",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"phonenumbers"
									]
								},
								"description": "Get phone number list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -52488128,\n  \"data\": [\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"veniam eiusmod ut voluptate\",\n          \"name\": \"reprehenderit\"\n        },\n        \"created_at\": \"minim reprehenderit\",\n        \"enabled\": false,\n        \"id\": \"culp\",\n        \"master_account_id\": \"minim\",\n        \"name\": \"aliqua nisi nostrud ea sunt\",\n        \"reseller_id\": -53209771,\n        \"sales_person\": {\n          \"first_name\": \"sint minim nostrud magna non\",\n          \"id\": \"consequat Excepteur quis\",\n          \"last_name\": \"aute in ex ut\"\n        },\n        \"timezone\": \"enim aliquip sunt\",\n        \"updated_at\": \"laboris\",\n        \"website\": \"commodo non tempor veniam\"\n      },\n      \"call_routing_type\": \"ut laborum\",\n      \"caller_id_prepend\": \"minim dolor\",\n      \"created_at\": \"cupidatat elit Ut dolor\",\n      \"e911_registration\": {\n        \"callback_number_id\": 46858048,\n        \"id26\": \"elit\",\n        \"name\": \"proident\"\n      },\n      \"holiday1\": \"ame\",\n      \"holiday2\": \"veniam\",\n      \"id\": -58639402,\n      \"id26\": \"sed mollit sunt ut\",\n      \"inbound_cnam_dip\": true,\n      \"main_number\": true,\n      \"main_number_last_updated\": \"ex ut\",\n      \"outbound_caller_id\": \"deserunt nulla exerc\",\n      \"pbx_connector\": {\n        \"id\": 18144590,\n        \"name\": \"nostrud elit do incididunt\"\n      },\n      \"phone_number\": \"mollit eiusmod\",\n      \"phone_number_status\": {\n        \"id\": -7143867,\n        \"name\": \"id esse\"\n      },\n      \"reseller\": {\n        \"address_city\": \"nostrud in culpa esse\",\n        \"address_country\": \"commodo sint\",\n        \"address_street_1\": \"mollit pariatur\",\n        \"address_street_2\": \"eiusmod\",\n        \"address_zip\": \"est eiusmod exercitation deserun\",\n        \"company_name\": \"amet proident exercitation pariatur\",\n        \"connectwise_integrated\": true,\n        \"created_at\": \"deserunt\",\n        \"dba\": \"in qui\",\n        \"demo_mode\": false,\n        \"enabled\": true,\n        \"id26\": \"irure nostrud\"\n      },\n      \"routing_to1\": \"ipsum Lorem culpa eu\",\n      \"routing_to2\": \"laborum eiusmod la\",\n      \"sms_routing\": 28943984,\n      \"status\": \"nulla labore\",\n      \"t38_faxing\": false,\n      \"updated_at\": \"tempor enim ut voluptate\"\n    },\n    {\n      \"account\": {\n        \"agent\": {\n          \"id\": \"occaecat Ut\",\n          \"name\": \"minim aliqua qui\"\n        },\n        \"created_at\": \"incididunt ipsum irure\",\n        \"enabled\": true,\n        \"id\": \"ullamco commodo pariatur do velit\",\n        \"master_account_id\": \"exercitation culpa id\",\n        \"name\": \"in cupidatat ut amet est\",\n        \"reseller_id\": 23662332,\n        \"sales_person\": {\n          \"first_name\": \"sed aliquip\",\n          \"id\": \"Excepteur\",\n          \"last_name\": \"sed nulla laboris\"\n        },\n        \"timezone\": \"nostrud est laboris irure cillum\",\n        \"updated_at\": \"dolore tempor\",\n        \"website\": \"id\"\n      },\n      \"call_routing_type\": \"Lorem in mi\",\n      \"caller_id_prepend\": \"amet adipisicing aliqua\",\n      \"created_at\": \"amet\",\n      \"e911_registration\": {\n        \"callback_number_id\": -29072826,\n        \"id26\": \"sint volupt\",\n        \"name\": \"Duis Excepteur\"\n      },\n      \"holiday1\": \"ex tempor\",\n      \"holiday2\": \"cillum esse sed\",\n      \"id\": 8979882,\n      \"id26\": \"aliqua\",\n      \"inbound_cnam_dip\": false,\n      \"main_number\": false,\n      \"main_number_last_updated\": \"nisi\",\n      \"outbound_caller_id\": \"ex fugiat laboris\",\n      \"pbx_connector\": {\n        \"id\": 50716088,\n        \"name\": \"ut officia\"\n      },\n      \"phone_number\": \"adipisi\",\n      \"phone_number_status\": {\n        \"id\": 25733634,\n        \"name\": \"deserunt aute cillum incididunt\"\n      },\n      \"reseller\": {\n        \"address_city\": \"sint pariatur ut\",\n        \"address_country\": \"tempor eu commodo ullamco\",\n        \"address_street_1\": \"tempor aliquip co\",\n        \"address_street_2\": \"irure voluptate\",\n        \"address_zip\": \"dolore commodo qu\",\n        \"company_name\": \"voluptate nisi elit\",\n        \"connectwise_integrated\": false,\n        \"created_at\": \"veniam Lorem ipsum fug\",\n        \"dba\": \"magna consequat non eiusmod Lorem\",\n        \"demo_mode\": false,\n        \"enabled\": false,\n        \"id26\": \"mollit laborum ea aliqua\"\n      },\n      \"routing_to1\": \"qui incididunt eu\",\n      \"routing_to2\": \"sit sint dolor est\",\n      \"sms_routing\": -19565114,\n      \"status\": \"cupidatat veniam ut laborum Ut\",\n      \"t38_faxing\": true,\n      \"updated_at\": \"reprehenderit in sint Lorem eu\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 18567270,\n    \"page\": -75919325,\n    \"total_pages\": -59943259,\n    \"total_rows\": 66444401\n  },\n  \"request_id\": \"aliquip irure minim\",\n  \"status\": \"nisi in\"\n}"
						}
					]
				},
				{
					"name": "Get phone number details",
					"id": "025e0266-7df0-4b38-a85e-ff12ba3b7bbe",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/phonenumbers/:phonenumber_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"phonenumbers",
								":phonenumber_idorid26"
							],
							"variable": [
								{
									"key": "phonenumber_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of phone number"
								}
							]
						},
						"description": "Get phone number details"
					},
					"response": [
						{
							"id": "d0b93758-39d8-4748-832a-8dfea889ff01",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/phonenumbers/:phonenumber_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"phonenumbers",
										":phonenumber_idorid26"
									],
									"variable": [
										{
											"key": "phonenumber_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of phone number"
										}
									]
								},
								"description": "Get phone number details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 48285299,\n  \"data\": {\n    \"account\": {\n      \"agent\": {\n        \"id\": \"velit non\",\n        \"name\": \"anim ex occaecat enim ut\"\n      },\n      \"created_at\": \"minim voluptate\",\n      \"enabled\": true,\n      \"id\": \"dolor in sed id dolor\",\n      \"master_account_id\": \"ut aliqua exercitation culpa ullam\",\n      \"name\": \"consectetur sint et adipisicing in\",\n      \"reseller_id\": 54494245,\n      \"sales_person\": {\n        \"first_name\": \"cillum\",\n        \"id\": \"quis\",\n        \"last_name\": \"dolore proident\"\n      },\n      \"timezone\": \"ipsum eu non\",\n      \"updated_at\": \"ipsum id tempor aliqua\",\n      \"website\": \"deserunt\"\n    },\n    \"call_routing_type\": \"aute tempor minim in ex\",\n    \"caller_id_prepend\": \"proident nisi\",\n    \"created_at\": \"reprehenderit Duis dolore\",\n    \"e911_registration\": {\n      \"callback_number_id\": -34110543,\n      \"id26\": \"Exc\",\n      \"name\": \"exercitation non\"\n    },\n    \"holiday1\": \"elit enim veniam dolor\",\n    \"holiday2\": \"ut magna nulla do\",\n    \"id\": -96087886,\n    \"id26\": \"id elit\",\n    \"inbound_cnam_dip\": false,\n    \"main_number\": true,\n    \"main_number_last_updated\": \"reprehenderit quis dolore Lorem\",\n    \"outbound_caller_id\": \"dolor\",\n    \"pbx_connector\": {\n      \"id\": 86842860,\n      \"name\": \"sit in quis sint\"\n    },\n    \"phone_number\": \"velit ad quis officia\",\n    \"phone_number_status\": {\n      \"id\": -38661276,\n      \"name\": \"ut fugiat\"\n    },\n    \"reseller\": {\n      \"address_city\": \"occaecat\",\n      \"address_country\": \"sunt sit pariatur\",\n      \"address_street_1\": \"occaecat dolor\",\n      \"address_street_2\": \"pariatur\",\n      \"address_zip\": \"esse Excepteur incididunt\",\n      \"company_name\": \"cupidatat Ut fugiat minim\",\n      \"connectwise_integrated\": false,\n      \"created_at\": \"dolore veniam\",\n      \"dba\": \"Excepteur in\",\n      \"demo_mode\": false,\n      \"enabled\": true,\n      \"id26\": \"dolore culpa sed nisi aliqua\"\n    },\n    \"routing_to1\": \"aliqua\",\n    \"routing_to2\": \"dolore\",\n    \"sms_routing\": -14560573,\n    \"status\": \"sed\",\n    \"t38_faxing\": false,\n    \"updated_at\": \"anim aute id\"\n  },\n  \"request_id\": \"ut labore ullamc\",\n  \"status\": \"amet dolore\"\n}"
						}
					]
				}
			],
			"id": "a725a5e7-e69d-40f7-96a2-6ca9ff77804f"
		},
		{
			"name": "todroutings",
			"item": [
				{
					"name": "Get time of day routing list",
					"id": "acf85cd1-1ea3-49c1-b1de-15d9e082028b",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/todroutings",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"todroutings"
							]
						},
						"description": "Get time of day routing list"
					},
					"response": [
						{
							"id": "35ddf5d5-52df-4821-8876-8dc6de1c3c40",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/todroutings",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"todroutings"
									]
								},
								"description": "Get time of day routing list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -40404891,\n  \"data\": [\n    {\n      \"after_forward_to\": -65045453,\n      \"after_forward_to_category\": \"id mollit voluptate laborum\",\n      \"created_at\": \"esse velit\",\n      \"during_forward_to\": -52648562,\n      \"during_forward_to_category\": \"cupidatat ullamco lab\",\n      \"fri_active\": true,\n      \"fri_begin\": \"dolor veniam est Lorem\",\n      \"fri_end\": \"elit\",\n      \"id\": 92932151,\n      \"id26\": \"adipisicing qui cillum\",\n      \"mon_active\": true,\n      \"mon_begin\": \"irure nisi ut\",\n      \"mon_end\": \"aute adipisicing magna\",\n      \"name\": \"exercitation irure ad magna\",\n      \"sat_active\": false,\n      \"sat_begin\": \"laboris in enim\",\n      \"sat_end\": \"labore aliquip amet ullamco adipisicing\",\n      \"sun_active\": false,\n      \"sun_begin\": \"dolore proident esse dolor\",\n      \"sun_end\": \"ad\",\n      \"thu_active\": true,\n      \"thu_begin\": \"occaecat esse magna officia enim\",\n      \"thu_end\": \"quis\",\n      \"timezone\": \"incididunt enim ullamco irure\",\n      \"tue_active\": true,\n      \"tue_begin\": \"Lorem\",\n      \"tue_end\": \"ea nulla mollit\",\n      \"updated_at\": \"dolore consequat magna veniam eiusmod\",\n      \"wed_active\": true,\n      \"wed_begin\": \"est commodo\",\n      \"wed_end\": \"sunt incididunt in qu\"\n    },\n    {\n      \"after_forward_to\": 14484211,\n      \"after_forward_to_category\": \"dolor vel\",\n      \"created_at\": \"voluptate amet\",\n      \"during_forward_to\": -28211464,\n      \"during_forward_to_category\": \"elit laborum\",\n      \"fri_active\": true,\n      \"fri_begin\": \"aliqua in sed sit\",\n      \"fri_end\": \"Excepteur consequat\",\n      \"id\": 56308154,\n      \"id26\": \"consequat anim minim in do\",\n      \"mon_active\": false,\n      \"mon_begin\": \"laboris in mollit do\",\n      \"mon_end\": \"culpa veniam sit off\",\n      \"name\": \"reprehenderit in\",\n      \"sat_active\": false,\n      \"sat_begin\": \"aute mollit occaecat ut ad\",\n      \"sat_end\": \"officia irure\",\n      \"sun_active\": true,\n      \"sun_begin\": \"dolor ipsum minim laborum\",\n      \"sun_end\": \"consequat veniam ex nulla amet\",\n      \"thu_active\": true,\n      \"thu_begin\": \"sed in nostrud mollit\",\n      \"thu_end\": \"culpa nulla in voluptate\",\n      \"timezone\": \"fugiat laboris nisi exercitation ea\",\n      \"tue_active\": true,\n      \"tue_begin\": \"ullamco dolor pariatur\",\n      \"tue_end\": \"ex elit veniam anim\",\n      \"updated_at\": \"anim commodo proident\",\n      \"wed_active\": true,\n      \"wed_begin\": \"enim et ea\",\n      \"wed_end\": \"Ut in consequat quis aliquip\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 81006424,\n    \"page\": -59158179,\n    \"total_pages\": -72189506,\n    \"total_rows\": 26593739\n  },\n  \"request_id\": \"ut reprehenderit velit\",\n  \"status\": \"proident nisi in dolor\"\n}"
						}
					]
				},
				{
					"name": "Get time of day routing details",
					"id": "eef5e70c-f8aa-4dae-b574-81c75a0aff0a",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/todroutings/:tod_routing_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"todroutings",
								":tod_routing_idorid26"
							],
							"variable": [
								{
									"key": "tod_routing_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of tod routing"
								}
							]
						},
						"description": "Get time of day routing details"
					},
					"response": [
						{
							"id": "c64522ba-8994-453a-bfff-94029802fab1",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/todroutings/:tod_routing_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"todroutings",
										":tod_routing_idorid26"
									],
									"variable": [
										{
											"key": "tod_routing_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of tod routing"
										}
									]
								},
								"description": "Get time of day routing details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 82425098,\n  \"data\": {\n    \"after_forward_to\": 31496709,\n    \"after_forward_to_category\": \"enim eiusmod incididunt\",\n    \"created_at\": \"non\",\n    \"during_forward_to\": -87624346,\n    \"during_forward_to_category\": \"cupidatat enim tempor\",\n    \"fri_active\": false,\n    \"fri_begin\": \"sunt non nulla culpa\",\n    \"fri_end\": \"tempor\",\n    \"id\": -24626276,\n    \"id26\": \"ut deserunt adipisicing\",\n    \"mon_active\": false,\n    \"mon_begin\": \"cillum ea sint\",\n    \"mon_end\": \"eiusmod est\",\n    \"name\": \"enim pariatur Ut\",\n    \"sat_active\": false,\n    \"sat_begin\": \"commodo cupidatat nostrud in\",\n    \"sat_end\": \"esse do eiusmod Except\",\n    \"sun_active\": false,\n    \"sun_begin\": \"consectetur dolor dolore voluptate\",\n    \"sun_end\": \"tempor qui\",\n    \"thu_active\": true,\n    \"thu_begin\": \"Ut non Excepteur consectetur\",\n    \"thu_end\": \"adipisicing cillum elit aute ad\",\n    \"timezone\": \"esse Excepteur non velit\",\n    \"tue_active\": true,\n    \"tue_begin\": \"id consectetur nisi\",\n    \"tue_end\": \"officia in\",\n    \"updated_at\": \"aliquip dolore\",\n    \"wed_active\": false,\n    \"wed_begin\": \"incididunt officia aliquip consequat\",\n    \"wed_end\": \"in dolore culpa\"\n  },\n  \"request_id\": \"Duis consectetur officia\",\n  \"status\": \"anim exercitation\"\n}"
						}
					]
				}
			],
			"id": "32438af3-97eb-4f0f-864a-05c76a70ca6e"
		},
		{
			"name": "virtualextensions",
			"item": [
				{
					"name": "Get virtual extension list",
					"id": "86e1c145-8b6e-4bbb-9ec8-bf70d6cd9eea",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/virtualextensions",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"virtualextensions"
							]
						},
						"description": "Get virtual extension list"
					},
					"response": [
						{
							"id": "b23fe067-c7bd-487b-a1c9-344060709618",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/virtualextensions",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"virtualextensions"
									]
								},
								"description": "Get virtual extension list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -65726344,\n  \"data\": [\n    {\n      \"extension\": 60280096,\n      \"name\": \"incididunt dolore amet Excepteur sit\",\n      \"route_to_category\": \"consectetur et\",\n      \"account_id\": -62495701,\n      \"created_at\": \"eiusmod voluptate\",\n      \"id\": 875057,\n      \"id26\": \"dolor\",\n      \"inbound_call_recording\": 40346687,\n      \"prepend_caller_id\": \"qui magna\",\n      \"reset_caller_id\": true,\n      \"route_to\": -61813828,\n      \"secondary_route_to\": 78860166,\n      \"secondary_route_to_category\": \"labore\",\n      \"seconds_to_ring\": -87497109,\n      \"updated_at\": \"eiusmod irure culpa deserunt\"\n    },\n    {\n      \"extension\": -91079502,\n      \"name\": \"sit sunt culpa et est\",\n      \"route_to_category\": \"Excepte\",\n      \"account_id\": -16095258,\n      \"created_at\": \"et ullamco aute incididunt\",\n      \"id\": -2379220,\n      \"id26\": \"officia nostrud laboris do\",\n      \"inbound_call_recording\": -1212347,\n      \"prepend_caller_id\": \"in veniam esse\",\n      \"reset_caller_id\": false,\n      \"route_to\": 45143977,\n      \"secondary_route_to\": 46974878,\n      \"secondary_route_to_category\": \"cillum laborum nostrud\",\n      \"seconds_to_ring\": -83514465,\n      \"updated_at\": \"dolore ex Ut eu ut\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": -65719184,\n    \"page\": 12346274,\n    \"total_pages\": 71928176,\n    \"total_rows\": -42022146\n  },\n  \"request_id\": \"aliquip minim Duis ullamco dolore\",\n  \"status\": \"id\"\n}"
						}
					]
				},
				{
					"name": "Get virtual extension details",
					"id": "54f5e107-7294-4d99-b45f-433852724767",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/virtualextensions/:virtual_extension_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"virtualextensions",
								":virtual_extension_idorid26"
							],
							"variable": [
								{
									"key": "virtual_extension_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of tod routing"
								}
							]
						},
						"description": "Get virtual extension details"
					},
					"response": [
						{
							"id": "48525b67-6ad5-45a0-9553-73bde492d6d0",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/virtualextensions/:virtual_extension_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"virtualextensions",
										":virtual_extension_idorid26"
									],
									"variable": [
										{
											"key": "virtual_extension_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of tod routing"
										}
									]
								},
								"description": "Get virtual extension details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": -2535567,\n  \"data\": {\n    \"extension\": 81280995,\n    \"name\": \"fugiat qui sit\",\n    \"route_to_category\": \"non\",\n    \"account_id\": 49456159,\n    \"created_at\": \"anim aliqua in\",\n    \"id\": -57261909,\n    \"id26\": \"mollit ex nisi\",\n    \"inbound_call_recording\": -15573295,\n    \"prepend_caller_id\": \"qui ipsum ex aute\",\n    \"reset_caller_id\": false,\n    \"route_to\": 81791568,\n    \"secondary_route_to\": -67415861,\n    \"secondary_route_to_category\": \"non ipsum commodo\",\n    \"seconds_to_ring\": 87243604,\n    \"updated_at\": \"mollit aliqua\"\n  },\n  \"request_id\": \"est ad\",\n  \"status\": \"consequat in\"\n}"
						}
					]
				}
			],
			"id": "3d67f4fc-7161-4f1b-84da-baa3c83e6ee7"
		},
		{
			"name": "voicemails",
			"item": [
				{
					"name": "Get voicemail box list",
					"id": "aebf6b81-1b80-41fc-9155-7423b159defd",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/voicemails",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"voicemails"
							]
						},
						"description": "Get voicemail box list"
					},
					"response": [
						{
							"id": "9fb21e61-d89f-4767-8d28-a46754f1e012",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/voicemails",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"voicemails"
									]
								},
								"description": "Get voicemail box list"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 10986748,\n  \"data\": [\n    {\n      \"additional_emails\": \"a\",\n      \"check_if_owner\": false,\n      \"created_at\": \"al\",\n      \"delete_after_notify\": false,\n      \"device_user_id\": -42647695,\n      \"enabled\": true,\n      \"id\": 99320536,\n      \"id26\": \"Excepteur occaecat\",\n      \"is_setup\": false,\n      \"mailbox\": \"veniam dolor aute commodo labore\",\n      \"media\": {\n        \"category\": \"nisi adipisicing\"\n      },\n      \"name\": \"qui eiusmod consequat sit enim\",\n      \"require_pin\": true,\n      \"send_to_boomea\": true,\n      \"skip_greeting\": false,\n      \"skip_instructions\": false,\n      \"timezone\": \"dolore deserunt reprehenderit in nisi\",\n      \"unavailable_media_id\": 12134772,\n      \"unavailable_media_type\": \"cupidatat consequat ea\",\n      \"updated_at\": \"Duis iru\",\n      \"voiceaxis_id\": true,\n      \"voip_id\": \"culpa\"\n    },\n    {\n      \"additional_emails\": \"dolor elit\",\n      \"check_if_owner\": false,\n      \"created_at\": \"aliqua laborum\",\n      \"delete_after_notify\": true,\n      \"device_user_id\": 36327697,\n      \"enabled\": false,\n      \"id\": 61743365,\n      \"id26\": \"officia enim dolor\",\n      \"is_setup\": false,\n      \"mailbox\": \"fugiat culpa laborum deserunt ea\",\n      \"media\": {\n        \"category\": \"cillum deserunt\"\n      },\n      \"name\": \"enim mollit adipisicing sunt\",\n      \"require_pin\": false,\n      \"send_to_boomea\": true,\n      \"skip_greeting\": false,\n      \"skip_instructions\": false,\n      \"timezone\": \"commodo sunt dolore\",\n      \"unavailable_media_id\": -28400971,\n      \"unavailable_media_type\": \"reprehenderit Excepteur\",\n      \"updated_at\": \"velit fugiat Lorem et\",\n      \"voiceaxis_id\": true,\n      \"voip_id\": \"ullamco sit mollit ea\"\n    }\n  ],\n  \"paginator\": {\n    \"limit\": 43628618,\n    \"page\": 58107458,\n    \"total_pages\": 59655255,\n    \"total_rows\": -364889\n  },\n  \"request_id\": \"in ess\",\n  \"status\": \"ex eiusmod do reprehenderit voluptate\"\n}"
						}
					]
				},
				{
					"name": "Get voicemail box details",
					"id": "a83e2e82-6d86-41fd-9aa6-4dc07b6189c2",
					"protocolProfileBehavior": {
						"disableBodyPruning": true
					},
					"request": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/voicemails/:voicemail_box_idorid26",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"voicemails",
								":voicemail_box_idorid26"
							],
							"variable": [
								{
									"key": "voicemail_box_idorid26",
									"value": "labore sin",
									"description": "(Required) Unique identifier of voicemail box"
								}
							]
						},
						"description": "Get voicemail box details"
					},
					"response": [
						{
							"id": "d6b8a57e-65b7-4967-b3ec-f3fc9212baaa",
							"name": "OK",
							"originalRequest": {
								"method": "GET",
								"header": [
									{
										"key": "Accept",
										"value": "application/json"
									}
								],
								"url": {
									"raw": "{{baseUrl}}/voicemails/:voicemail_box_idorid26",
									"host": [
										"{{baseUrl}}"
									],
									"path": [
										"voicemails",
										":voicemail_box_idorid26"
									],
									"variable": [
										{
											"key": "voicemail_box_idorid26",
											"value": "labore sin",
											"description": "(Required) Unique identifier of voicemail box"
										}
									]
								},
								"description": "Get voicemail box details"
							},
							"status": "OK",
							"code": 200,
							"_postman_previewlanguage": "json",
							"header": [
								{
									"key": "Content-Type",
									"value": "application/json"
								}
							],
							"cookie": [],
							"body": "{\n  \"code\": 94637808,\n  \"data\": {\n    \"additional_emails\": \"irure Lorem nisi eu\",\n    \"check_if_owner\": false,\n    \"created_at\": \"elit in consectetur mollit\",\n    \"delete_after_notify\": true,\n    \"device_user_id\": 78625621,\n    \"enabled\": true,\n    \"id\": 70696184,\n    \"id26\": \"mollit\",\n    \"is_setup\": true,\n    \"mailbox\": \"consectetur mollit\",\n    \"media\": {\n      \"category\": \"veniam laboris sed\"\n    },\n    \"name\": \"\",\n    \"require_pin\": true,\n    \"send_to_boomea\": false,\n    \"skip_greeting\": true,\n    \"skip_instructions\": false,\n    \"timezone\": \"sin\",\n    \"unavailable_media_id\": 83653281,\n    \"unavailable_media_type\": \"irure \",\n    \"updated_at\": \"consequat consectetur sed\",\n    \"voiceaxis_id\": false,\n    \"voip_id\": \"in\"\n  },\n  \"request_id\": \"officia sint\",\n  \"status\": \"irure laborum\"\n}"
						}
					]
				}
			],
			"id": "45a8a890-1392-490f-9036-920371fda8a9"
		},
		{
			"name": "Get settings of an account",
			"id": "c7610fc8-9b2d-4ce7-8228-86b9cdae907d",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Accept",
						"value": "application/json"
					}
				],
				"url": {
					"raw": "{{baseUrl}}/accountsettings",
					"host": [
						"{{baseUrl}}"
					],
					"path": [
						"accountsettings"
					]
				},
				"description": "Get settings of an account"
			},
			"response": [
				{
					"id": "391a3e7e-c687-47a9-8676-a41f0edb7907",
					"name": "OK",
					"originalRequest": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/accountsettings",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"accountsettings"
							]
						},
						"description": "Get settings of an account"
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Content-Type",
							"value": "application/json"
						}
					],
					"cookie": [],
					"body": "{\n  \"code\": 92945089,\n  \"data\": {\n    \"check_voicemail\": false,\n    \"confirm_match\": true,\n    \"created\": \"Duis laborum dolor\",\n    \"default_caller_id\": \"deserunt\",\n    \"default_on_hold_media_id\": -7766935,\n    \"default_on_hold_type\": \"proident irure quis laboris\",\n    \"direct_to_voicemail\": false,\n    \"directory_search\": \"quis laboris\",\n    \"disable_call_forward\": true,\n    \"disable_hot_desking\": false,\n    \"dynamic_cid_account_enabled\": true,\n    \"enable_call_forward\": true,\n    \"enable_hot_desking\": true,\n    \"intercom\": false,\n    \"international_pin\": \"dolor dolore labore\",\n    \"modified\": \"aute velit consectetur laboris\",\n    \"notes\": \"cupidatat sit\",\n    \"off_net_caller_id\": 28318630,\n    \"park_and_retrieve\": true,\n    \"park_presence\": false,\n    \"park_timeout\": 46298352,\n    \"privacy\": false,\n    \"realm\": \"deserunt in\",\n    \"retrieve\": false,\n    \"sort_by\": \"anim exercitation\",\n    \"timezone\": \"quis labore\",\n    \"toggle_call_forward\": false,\n    \"toggle_hot_desking\": true,\n    \"update_call_forward\": false,\n    \"valet\": true,\n    \"voip_id\": \"magna\"\n  },\n  \"request_id\": \"dolor officia c\",\n  \"status\": \"tempor ipsum sed deserunt\"\n}"
				}
			]
		},
		{
			"name": "Get blacklist of an account",
			"id": "1924075e-1e7e-4f03-853e-efda5802d1f6",
			"protocolProfileBehavior": {
				"disableBodyPruning": true
			},
			"request": {
				"method": "GET",
				"header": [
					{
						"key": "Accept",
						"value": "application/json"
					}
				],
				"url": {
					"raw": "{{baseUrl}}/blacklist",
					"host": [
						"{{baseUrl}}"
					],
					"path": [
						"blacklist"
					]
				},
				"description": "Get blacklist of an account"
			},
			"response": [
				{
					"id": "0e594e45-792f-4d92-b1e2-883b9c7603b1",
					"name": "OK",
					"originalRequest": {
						"method": "GET",
						"header": [
							{
								"key": "Accept",
								"value": "application/json"
							}
						],
						"url": {
							"raw": "{{baseUrl}}/blacklist",
							"host": [
								"{{baseUrl}}"
							],
							"path": [
								"blacklist"
							]
						},
						"description": "Get blacklist of an account"
					},
					"status": "OK",
					"code": 200,
					"_postman_previewlanguage": "json",
					"header": [
						{
							"key": "Content-Type",
							"value": "application/json"
						}
					],
					"cookie": [],
					"body": "{\n  \"code\": 4186998,\n  \"data\": {\n    \"block_anonymous\": true,\n    \"numbers\": \"quis veniam\"\n  },\n  \"request_id\": \"enim dolor aute\",\n  \"status\": \"do\"\n}"
				}
			]
		}
	],
	"variable": [
		{
			"id": "99e74250-3cd5-4c69-abdd-9f0d5e83df58",
			"key": "baseUrl",
			"value": "//api.titan.host/api/v2",
			"type": "string"
		}
	]
}
