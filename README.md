# WLC-Titan-API
WLC TO GDMS
WLC TO CALL2TEAMS


{
  "swagger": "2.0",
  "info": {
    "description": "Titan is your API gateway to UC Communications.  \nThe URL endpoint is:  \n`https://api.titan.host/api/v2`\n\n![Titan Logo](https://docs.titan.host/Graphic01_WhiteBG_PNG.png)\n",
    "title": "Titan API",
    "contact": {},
    "version": "2.0"
  },
  "host": "api.titan.host",
  "basePath": "/api/v2",
  "paths": {
    "/accountsettings": {
      "get": {
        "description": "Get settings of an account",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Account Settings"
        ],
        "summary": "Get settings of an account",
        "operationId": "AccountSettingsGet",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.AccountSettingDoc"
            }
          }
        }
      }
    },
    "/blacklist": {
      "get": {
        "description": "Get blacklist of an account",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Blacklist"
        ],
        "summary": "Get blacklist of an account",
        "operationId": "BlacklistGet",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.BlacklistDoc"
            }
          }
        }
      }
    },
    "/callqueues": {
      "get": {
        "description": "Get call queue list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Call Center Queues"
        ],
        "summary": "Get call queue list",
        "operationId": "CallQueueGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.CallQueueListDoc"
            }
          }
        }
      }
    },
    "/callqueues/{callqueue_idorid26}": {
      "get": {
        "description": "Get call queue details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Call Center Queues"
        ],
        "summary": "Get call queue details",
        "operationId": "CallQueueGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of call queue",
            "name": "callqueue_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.CallQueueDoc"
            }
          }
        }
      }
    },
    "/conferences": {
      "get": {
        "description": "Get conference list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Conferences"
        ],
        "summary": "Get conference list",
        "operationId": "ConferenceGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.ConferenceListDoc"
            }
          }
        }
      }
    },
    "/conferences/{conference_idorid26}": {
      "get": {
        "description": "Get conference details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Conferences"
        ],
        "summary": "Get conference details",
        "operationId": "ConferenceGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of conference",
            "name": "conference_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.ConferenceDoc"
            }
          }
        }
      }
    },
    "/devices": {
      "get": {
        "description": "Get device list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Devices"
        ],
        "summary": "Get device list",
        "operationId": "DeviceGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DeviceListDoc"
            }
          }
        }
      }
    },
    "/devices/{device_idorid26}": {
      "get": {
        "description": "Get device details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Devices"
        ],
        "summary": "Get device details",
        "operationId": "DeviceGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of device",
            "name": "device_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DeviceDoc"
            }
          }
        }
      }
    },
    "/deviceusers": {
      "get": {
        "description": "Get device user list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Device Users"
        ],
        "summary": "Get device user list",
        "operationId": "DeviceUserGetAll",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DeviceUserListDoc"
            }
          }
        }
      }
    },
    "/deviceusers/{device_user_idorid26}": {
      "get": {
        "description": "Get device user details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Device Users"
        ],
        "summary": "Get device user details",
        "operationId": "DeviceUserGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of device user",
            "name": "device_user_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DeviceUserDoc"
            }
          }
        }
      }
    },
    "/disa": {
      "get": {
        "description": "Get disa list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP DISA"
        ],
        "summary": "Get disa list",
        "operationId": "DisaGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DisaListDoc"
            }
          }
        }
      }
    },
    "/disa/{disa_idorid26}": {
      "get": {
        "description": "Get disa details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP DISA"
        ],
        "summary": "Get disa details",
        "operationId": "DisaGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of disa",
            "name": "disa_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.DisaDoc"
            }
          }
        }
      }
    },
    "/e911registrations": {
      "get": {
        "description": "Get e911 registration list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP E911 Registration"
        ],
        "summary": "Get e911 registration list",
        "operationId": "E911RegistrationGetAll",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.E911RegistrationListDoc"
            }
          }
        }
      }
    },
    "/e911registrations/{e911_registration_idorid26}": {
      "get": {
        "description": "Get e911 registration details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP E911 Registration"
        ],
        "summary": "Get e911 registration details",
        "operationId": "E911RegistrationGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of e911 registration",
            "name": "e911_registration_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.E911RegistrationDoc"
            }
          }
        }
      }
    },
    "/faxboxes": {
      "get": {
        "description": "Get fax box list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Fax Boxes"
        ],
        "summary": "Get fax box list",
        "operationId": "FaxBoxGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.FaxBoxListDoc"
            }
          }
        }
      }
    },
    "/faxboxes/{fax_box_idorid26}": {
      "get": {
        "description": "Get fax  box details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Fax Boxes"
        ],
        "summary": "Get fax box details",
        "operationId": "FaxBoxGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of fax box",
            "name": "fax_box_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.FaxBoxDoc"
            }
          }
        }
      }
    },
    "/groups": {
      "get": {
        "description": "Get group list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Groups"
        ],
        "summary": "Get group list",
        "operationId": "GroupGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.GroupListDoc"
            }
          }
        }
      }
    },
    "/groups/{group_idorid26}": {
      "get": {
        "description": "Get group details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Groups"
        ],
        "summary": "Get group details",
        "operationId": "GroupGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of group",
            "name": "group_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.GroupDoc"
            }
          }
        }
      }
    },
    "/holidayroutingsettings": {
      "get": {
        "description": "Get holiday routing list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Holiday Routing"
        ],
        "summary": "Get holiday routing list",
        "operationId": "HolidayRoutingSettingGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.HolidayRoutingSettingListDoc"
            }
          }
        }
      }
    },
    "/holidayroutingsettings/{holiday_routing_setting_idorid26}": {
      "get": {
        "description": "Get holiday routing details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Holiday Routing"
        ],
        "summary": "Get holiday routing details",
        "operationId": "HolidayRoutingSettingGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of HolidayRoutingSetting",
            "name": "holiday_routing_setting_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.HolidayRoutingSettingDoc"
            }
          }
        }
      }
    },
    "/mediafiles": {
      "get": {
        "description": "Get media file list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Media"
        ],
        "summary": "Get media file list",
        "operationId": "MediaFileGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.MediaFileListDoc"
            }
          }
        }
      }
    },
    "/mediafiles/{media_file_idorid26}": {
      "get": {
        "description": "Get media file details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Media"
        ],
        "summary": "Get media file details",
        "operationId": "MediaFileGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of MediaFile",
            "name": "media_file_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.MediaFileDoc"
            }
          }
        }
      }
    },
    "/menus": {
      "get": {
        "description": "Get menu list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Menus"
        ],
        "summary": "Get menu list",
        "operationId": "MenuGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.MenuListDoc"
            }
          }
        }
      }
    },
    "/menus/{menu_idorid26}": {
      "get": {
        "description": "Get menu details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Menus"
        ],
        "summary": "Get menu details",
        "operationId": "MenuGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of Menu",
            "name": "menu_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.MenuDoc"
            }
          }
        }
      }
    },
    "/pbxconnectors": {
      "get": {
        "description": "Get PBX connector list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP PBX Connector"
        ],
        "summary": "Get PBX connector list",
        "operationId": "PbxConnectorGetAll",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.PbxConnectorListDoc"
            }
          }
        }
      }
    },
    "/pbxconnectors/{pbx_connector_idorid26}": {
      "get": {
        "description": "Get PBX connector details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP PBX Connector"
        ],
        "summary": "Get PBX connector details",
        "operationId": "PbxConnectorGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of pbx connector",
            "name": "pbx_connector_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.PbxConnectorDoc"
            }
          }
        }
      }
    },
    "/phonenumbers": {
      "get": {
        "description": "Get phone number list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Phone Numbers"
        ],
        "summary": "Get phone number list",
        "operationId": "PhoneNumberGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.PhoneNumberListDoc"
            }
          }
        }
      }
    },
    "/phonenumbers/{phonenumber_idorid26}": {
      "get": {
        "description": "Get phone number details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Phone Numbers"
        ],
        "summary": "Get phone number details",
        "operationId": "PhoneNumberGetSingle",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of phone number",
            "name": "phonenumber_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.PhoneNumberDoc"
            }
          }
        }
      }
    },
    "/todroutings": {
      "get": {
        "description": "Get time of day routing list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Time Of Day Routing"
        ],
        "summary": "Get time of day routing list",
        "operationId": "TodRoutingGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.TodRoutingListDoc"
            }
          }
        }
      }
    },
    "/todroutings/{tod_routing_idorid26}": {
      "get": {
        "description": "Get time of day routing details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Time Of Day Routing"
        ],
        "summary": "Get time of day routing details",
        "operationId": "TodRoutingGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of tod routing",
            "name": "tod_routing_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.TodRoutingDoc"
            }
          }
        }
      }
    },
    "/virtualextensions": {
      "get": {
        "description": "Get virtual extension list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Virtual Extensions"
        ],
        "summary": "Get virtual extension list",
        "operationId": "VirtualExtensionGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.VirtualExtensionListDoc"
            }
          }
        }
      }
    },
    "/virtualextensions/{virtual_extension_idorid26}": {
      "get": {
        "description": "Get virtual extension details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Virtual Extensions"
        ],
        "summary": "Get virtual extension details",
        "operationId": "VirtualExtensionGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of tod routing",
            "name": "virtual_extension_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.VirtualExtensionDoc"
            }
          }
        }
      }
    },
    "/voicemails": {
      "get": {
        "description": "Get voicemail box list",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Voicemail Boxes"
        ],
        "summary": "Get voicemail box list",
        "operationId": "VoicemailBoxGetList",
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.VoicemailBoxListDoc"
            }
          }
        }
      }
    },
    "/voicemails/{voicemail_box_idorid26}": {
      "get": {
        "description": "Get voicemail box details",
        "produces": [
          "application/json"
        ],
        "tags": [
          "VoIP Voicemail Boxes"
        ],
        "summary": "Get voicemail box details",
        "operationId": "VoicemailBoxGet",
        "parameters": [
          {
            "type": "string",
            "description": "Unique identifier of voicemail box",
            "name": "voicemail_box_idorid26",
            "in": "path",
            "required": true
          }
        ],
        "responses": {
          "200": {
            "description": "OK",
            "schema": {
              "$ref": "#/definitions/models.VoicemailBoxDoc"
            }
          }
        }
      }
    }
  },
  "definitions": {
    "models.AccountDeviceUser": {
      "type": "object",
      "properties": {
        "agent": {
          "$ref": "#/definitions/models.Agent"
        },
        "created_at": {
          "type": "string"
        },
        "enabled": {
          "type": "boolean"
        },
        "id": {
          "type": "string"
        },
        "master_account_id": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "reseller_id": {
          "type": "integer"
        },
        "sales_person": {
          "$ref": "#/definitions/models.UserAccount"
        },
        "timezone": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        },
        "website": {
          "type": "string"
        }
      }
    },
    "models.AccountSettingAssociation": {
      "type": "object",
      "properties": {
        "check_voicemail": {
          "type": "boolean"
        },
        "confirm_match": {
          "type": "boolean"
        },
        "created": {
          "type": "string"
        },
        "default_caller_id": {
          "type": "string"
        },
        "default_on_hold_media_id": {
          "type": "integer"
        },
        "default_on_hold_type": {
          "type": "string"
        },
        "direct_to_voicemail": {
          "type": "boolean"
        },
        "directory_search": {
          "type": "string"
        },
        "disable_call_forward": {
          "type": "boolean"
        },
        "disable_hot_desking": {
          "type": "boolean"
        },
        "dynamic_cid_account_enabled": {
          "type": "boolean"
        },
        "enable_call_forward": {
          "type": "boolean"
        },
        "enable_hot_desking": {
          "type": "boolean"
        },
        "intercom": {
          "type": "boolean"
        },
        "international_pin": {
          "type": "string"
        },
        "modified": {
          "type": "string"
        },
        "notes": {
          "type": "string"
        },
        "off_net_caller_id": {
          "type": "integer"
        },
        "park_and_retrieve": {
          "type": "boolean"
        },
        "park_presence": {
          "type": "boolean"
        },
        "park_timeout": {
          "type": "integer"
        },
        "privacy": {
          "type": "boolean"
        },
        "realm": {
          "type": "string"
        },
        "retrieve": {
          "type": "boolean"
        },
        "sort_by": {
          "type": "string"
        },
        "timezone": {
          "type": "string"
        },
        "toggle_call_forward": {
          "type": "boolean"
        },
        "toggle_hot_desking": {
          "type": "boolean"
        },
        "update_call_forward": {
          "type": "boolean"
        },
        "valet": {
          "type": "boolean"
        },
        "voip_id": {
          "type": "string"
        }
      }
    },
    "models.AccountSettingDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.AccountSettingAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.Agent": {
      "type": "object",
      "properties": {
        "id": {
          "type": "string"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.Blacklist": {
      "type": "object",
      "properties": {
        "block_anonymous": {
          "type": "boolean"
        },
        "numbers": {
          "type": "string"
        }
      }
    },
    "models.BlacklistDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.Blacklist"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.CallQueueDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.PhoneAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.CallQueueListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.PhoneAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.ConferenceAssociation": {
      "type": "object",
      "properties": {
        "assigned_to": {
          "$ref": "#/definitions/models.DeviceDeviceUserAssoc"
        },
        "created_at": {
          "type": "string"
        },
        "device_user_id": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "join_deaf": {
          "type": "boolean"
        },
        "join_muted": {
          "type": "boolean"
        },
        "moderator_pin": {
          "type": "string"
        },
        "moderators": {
          "type": "array",
          "items": {
            "type": "object",
            "additionalProperties": true
          }
        },
        "name": {
          "type": "string"
        },
        "numbers": {
          "type": "string"
        },
        "pin": {
          "type": "integer"
        },
        "site": {
          "$ref": "#/definitions/models.Site"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.ConferenceDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.ConferenceAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.ConferenceListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.ConferenceAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DeviceAssociation": {
      "type": "object",
      "properties": {
        "CELT_48": {
          "type": "boolean"
        },
        "CELT_64": {
          "type": "boolean"
        },
        "G722_16": {
          "type": "boolean"
        },
        "G722_32": {
          "type": "boolean"
        },
        "PCMA": {
          "type": "boolean"
        },
        "PCMU": {
          "type": "boolean"
        },
        "additional_emails": {
          "type": "string"
        },
        "custom_code": {
          "type": "string"
        },
        "device_line_keys": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.DeviceLineKey"
          }
        },
        "device_template": {
          "$ref": "#/definitions/models.DeviceTemplate"
        },
        "device_type": {
          "type": "string"
        },
        "device_user": {
          "$ref": "#/definitions/models.DeviceDeviceUserAssoc"
        },
        "encryption": {
          "type": "integer"
        },
        "encryption_type": {
          "type": "string"
        },
        "expire_seconds": {
          "type": "integer"
        },
        "extension": {
          "type": "string"
        },
        "has_voicemail": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "invite_format": {
          "type": "string"
        },
        "keep_caller_id": {
          "type": "boolean"
        },
        "mac_address": {
          "type": "string"
        },
        "manufacturer": {
          "$ref": "#/definitions/models.Manufacturer"
        },
        "manufacturer_model": {
          "$ref": "#/definitions/models.ManufacturerModel"
        },
        "manufacturer_ringer": {
          "$ref": "#/definitions/models.ManufacturerRinger"
        },
        "media_category": {
          "type": "string"
        },
        "media_category_type": {
          "type": "string"
        },
        "media_id": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "number": {
          "type": "string"
        },
        "peer_to_peer": {
          "type": "string"
        },
        "peer_to_peer_type": {
          "type": "string"
        },
        "phone": {
          "$ref": "#/definitions/models.DevicePhoneAssoc"
        },
        "require_keypress": {
          "type": "boolean"
        },
        "restrict_caribbean": {
          "type": "string"
        },
        "restrict_did_us": {
          "type": "string"
        },
        "restrict_international": {
          "type": "string"
        },
        "restrict_toll_us": {
          "type": "string"
        },
        "restrict_tollfree_us": {
          "type": "string"
        },
        "sip_authentication_method": {
          "type": "string"
        },
        "sip_password": {
          "type": "string"
        },
        "sip_realm": {
          "type": "string"
        },
        "sip_username": {
          "type": "string"
        },
        "site": {
          "$ref": "#/definitions/models.Site"
        },
        "virtual_extension": {
          "$ref": "#/definitions/models.VirtualExtensionAssoc"
        },
        "vm_to_email_enabled": {
          "type": "integer"
        },
        "voicemail_box": {
          "$ref": "#/definitions/models.VoicemailBox"
        },
        "voip_id": {
          "type": "string"
        }
      }
    },
    "models.DeviceDeviceUserAssoc": {
      "type": "object",
      "properties": {
        "extension": {
          "type": "string"
        },
        "first_name": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "last_name": {
          "type": "string"
        }
      }
    },
    "models.DeviceDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.DeviceAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DeviceLineKey": {
      "type": "object",
      "properties": {
        "data": {
          "type": "string"
        },
        "device_id": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "line_key_type": {
          "type": "string"
        },
        "line_key_type_id": {
          "type": "integer"
        },
        "num": {
          "type": "integer"
        },
        "title": {
          "type": "string"
        }
      }
    },
    "models.DeviceListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.DeviceAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DevicePhoneAssoc": {
      "type": "object",
      "properties": {
        "phone_number": {
          "type": "string"
        }
      }
    },
    "models.DeviceTemplate": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "manufacturer_id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.DeviceUserAssociation": {
      "type": "object",
      "properties": {
        "account": {
          "$ref": "#/definitions/models.AccountDeviceUser"
        },
        "account_id": {
          "description": "Unique identifier of account",
          "type": "integer"
        },
        "add_to_directory": {
          "type": "boolean"
        },
        "agent_status": {
          "type": "boolean"
        },
        "busy_route": {
          "type": "string"
        },
        "busy_route_category": {
          "type": "string"
        },
        "caller_id_external_number_id": {
          "description": "Off Net Caller ID Number",
          "type": "string"
        },
        "caller_id_internal_name": {
          "description": "On Net Caller ID Name",
          "type": "string"
        },
        "caller_id_internal_number": {
          "description": "On Net Caller ID Number",
          "type": "string"
        },
        "conference": {
          "$ref": "#/definitions/models.DeviceUserConferenceAssociation"
        },
        "created_at": {
          "type": "string"
        },
        "devices": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.DeviceUserDeviceAssoc"
          }
        },
        "dynamic_call_recording": {
          "type": "boolean"
        },
        "e911_registration_user": {
          "$ref": "#/definitions/models.E911RegistrationDeviceUser"
        },
        "email": {
          "type": "string"
        },
        "first_name": {
          "type": "string"
        },
        "fmfm": {
          "type": "boolean"
        },
        "has_voicemail": {
          "type": "boolean"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "description": "Unique identifier of device user",
          "type": "string"
        },
        "inbound_call_recording": {
          "type": "boolean"
        },
        "last_name": {
          "type": "string"
        },
        "mobile_app_access": {
          "type": "boolean"
        },
        "mobile_presence": {
          "type": "boolean"
        },
        "not_available_route_category": {
          "type": "string"
        },
        "not_registered_number": {
          "type": "string"
        },
        "outbound_call_recording": {
          "type": "boolean"
        },
        "phone_number": {
          "$ref": "#/definitions/models.PhoneAssociationDeviceUser"
        },
        "prepend_caller_id": {
          "type": "string"
        },
        "reset_caller_id": {
          "type": "boolean"
        },
        "seconds_to_ring": {
          "type": "integer"
        },
        "timezone": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        },
        "vm_to_email_enabled": {
          "type": "boolean"
        },
        "voicemail_box": {
          "$ref": "#/definitions/models.VoicemailBox"
        },
        "webphone_e911_registration_id": {
          "type": "integer"
        },
        "webphone_enabled": {
          "type": "boolean"
        },
        "when_found_route_category": {
          "type": "string"
        }
      }
    },
    "models.DeviceUserConferenceAssociation": {
      "type": "object",
      "properties": {
        "created_at": {
          "type": "string"
        },
        "device_user_id": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "join_deaf": {
          "type": "boolean"
        },
        "join_muted": {
          "type": "boolean"
        },
        "moderator_pin": {
          "type": "string"
        },
        "moderators": {
          "type": "array",
          "items": {
            "type": "object",
            "additionalProperties": true
          }
        },
        "name": {
          "type": "string"
        },
        "numbers": {
          "type": "string"
        },
        "pin": {
          "type": "integer"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.DeviceUserDeviceAssoc": {
      "type": "object",
      "properties": {
        "additional_emails": {
          "type": "string"
        },
        "device_template": {
          "$ref": "#/definitions/models.DeviceTemplate"
        },
        "device_type": {
          "type": "string"
        },
        "extension": {
          "type": "string"
        },
        "has_voicemail": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "keep_caller_id": {
          "type": "boolean"
        },
        "mac_address": {
          "type": "string"
        },
        "manufacturer": {
          "$ref": "#/definitions/models.Manufacturer"
        },
        "manufacturer_model": {
          "$ref": "#/definitions/models.ManufacturerModel"
        },
        "name": {
          "type": "string"
        },
        "number": {
          "type": "string"
        },
        "require_keypress": {
          "type": "boolean"
        },
        "restrict_caribbean": {
          "type": "string"
        },
        "restrict_did_us": {
          "type": "string"
        },
        "restrict_international": {
          "type": "string"
        },
        "restrict_toll_us": {
          "type": "string"
        },
        "restrict_tollfree_us": {
          "type": "string"
        },
        "vm_to_email_enabled": {
          "type": "integer"
        }
      }
    },
    "models.DeviceUserDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.DeviceUserAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DeviceUserEfax": {
      "type": "object",
      "properties": {
        "email": {
          "type": "string"
        },
        "first_name": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "last_name": {
          "type": "string"
        }
      }
    },
    "models.DeviceUserListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.DeviceUserAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DisaDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.DisaPhoneNumberAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DisaListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.DisaPhoneNumberAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.DisaPhoneNumber": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "phone_number": {
          "type": "string"
        }
      }
    },
    "models.DisaPhoneNumberAssociation": {
      "type": "object",
      "properties": {
        "caller_id": {
          "$ref": "#/definitions/models.DisaPhoneNumber"
        },
        "created_at": {
          "type": "string"
        },
        "description": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "pin": {
          "type": "integer"
        },
        "retries": {
          "type": "integer"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationAssoc": {
      "type": "object",
      "properties": {
        "callback_number_id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationAssociation": {
      "type": "object",
      "properties": {
        "account_id": {
          "type": "integer"
        },
        "address_city": {
          "type": "string"
        },
        "address_state": {
          "type": "string"
        },
        "address_street_1": {
          "type": "string"
        },
        "address_street_2": {
          "type": "string"
        },
        "address_zip": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "custom_provider": {
          "type": "integer"
        },
        "devices": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.E911RegistrationDevices"
          }
        },
        "emails": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.E911RegistrationEmails"
          }
        },
        "enabled": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "latitude": {
          "type": "number"
        },
        "longitude": {
          "type": "number"
        },
        "name": {
          "type": "string"
        },
        "phone": {
          "$ref": "#/definitions/models.PhoneE911Registration"
        },
        "site_id": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationDeviceUser": {
      "type": "object",
      "properties": {
        "address_city": {
          "type": "string"
        },
        "address_street_1": {
          "type": "integer"
        },
        "callback_number_id": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationDeviceUserName": {
      "type": "object",
      "properties": {
        "first_name": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "last_name": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationDevices": {
      "type": "object",
      "properties": {
        "device_type": {
          "type": "string"
        },
        "device_user_id": {
          "type": "integer"
        },
        "e911_registration_id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        },
        "user": {
          "$ref": "#/definitions/models.E911RegistrationDeviceUserName"
        }
      }
    },
    "models.E911RegistrationDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.E911RegistrationAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationEmails": {
      "type": "object",
      "properties": {
        "e911_registration_id": {
          "type": "integer"
        },
        "email": {
          "type": "string"
        },
        "verified": {
          "type": "boolean"
        }
      }
    },
    "models.E911RegistrationListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.E911RegistrationAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.E911RegistrationPbxConnector": {
      "type": "object",
      "properties": {
        "address_city": {
          "type": "string"
        },
        "address_state": {
          "type": "string"
        },
        "address_street_1": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        }
      }
    },
    "models.Efax": {
      "type": "object",
      "properties": {
        "allowed_senders": {
          "type": "string"
        },
        "caller_id_name": {
          "type": "string"
        },
        "caller_id_number": {
          "$ref": "#/definitions/models.PhoneE911Registration"
        },
        "created_at": {
          "type": "string"
        },
        "device_user": {
          "$ref": "#/definitions/models.DeviceUserEfax"
        },
        "domain_2": {
          "type": "string"
        },
        "email_address": {
          "type": "string"
        },
        "fax_box_domain": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "outbound_faxing": {
          "type": "boolean"
        },
        "retries": {
          "type": "string"
        },
        "sent_receipts": {
          "type": "boolean"
        },
        "timezone": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.FaxBoxDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.Efax"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.FaxBoxListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.Efax"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.GroupAssociation": {
      "type": "object",
      "properties": {
        "account_id": {
          "type": "integer"
        },
        "after_group_forward_call": {
          "type": "object",
          "additionalProperties": true
        },
        "callflow_voip_id": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "group_endpoints": {
          "type": "array",
          "items": {
            "type": "object",
            "additionalProperties": true
          }
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "inbound_call_recording": {
          "type": "boolean"
        },
        "media": {
          "$ref": "#/definitions/models.MediaFileAssoc"
        },
        "media_id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        },
        "prepend_to_caller_id_name": {
          "type": "string"
        },
        "repeat": {
          "type": "integer"
        },
        "reset_caller_id": {
          "type": "boolean"
        },
        "ring_all_sequentially": {
          "type": "string"
        },
        "seconds_to_ring": {
          "type": "integer"
        },
        "selector": {
          "type": "string"
        },
        "should_play_media": {
          "type": "boolean"
        },
        "updated_at": {
          "type": "string"
        },
        "voip_id": {
          "type": "string"
        }
      }
    },
    "models.GroupDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.GroupAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.GroupListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.GroupAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.HolidayRoutingSettingAssociation": {
      "type": "object",
      "properties": {
        "activate": {
          "type": "boolean"
        },
        "all_day": {
          "type": "boolean"
        },
        "created_at": {
          "type": "string"
        },
        "enabled": {
          "type": "boolean"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "monthly_day": {
          "type": "string"
        },
        "monthly_ordinal": {
          "type": "string"
        },
        "monthly_type": {
          "type": "string"
        },
        "monthly_weekday": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "repeats": {
          "type": "string"
        },
        "site_id": {
          "type": "integer"
        },
        "start_date": {
          "type": "string"
        },
        "summary": {
          "type": "string"
        },
        "time_begin": {
          "type": "string"
        },
        "time_end": {
          "type": "string"
        },
        "type": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        },
        "weekly_weekday": {
          "type": "string"
        },
        "yearly_day": {
          "type": "string"
        },
        "yearly_month": {
          "type": "string"
        },
        "yearly_ordinal": {
          "type": "string"
        },
        "yearly_type": {
          "type": "string"
        },
        "yearly_weekday": {
          "type": "string"
        }
      }
    },
    "models.HolidayRoutingSettingDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.HolidayRoutingSettingAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.HolidayRoutingSettingListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.HolidayRoutingSettingAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.Manufacturer": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "title": {
          "type": "string"
        }
      }
    },
    "models.ManufacturerModel": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "title": {
          "type": "string"
        }
      }
    },
    "models.ManufacturerRinger": {
      "type": "object",
      "properties": {
        "display_name": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "manufacturer_id": {
          "type": "integer"
        }
      }
    },
    "models.MediaFile": {
      "type": "object",
      "properties": {
        "category": {
          "type": "string"
        }
      }
    },
    "models.MediaFileAssoc": {
      "type": "object",
      "properties": {
        "category": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.MediaFileDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.MediaFiles"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.MediaFileListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.MediaFiles"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.MediaFiles": {
      "type": "object",
      "properties": {
        "category": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "description": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.Menu": {
      "type": "object",
      "properties": {
        "allow_extension": {
          "type": "boolean"
        },
        "allow_record_from_outside": {
          "type": "boolean"
        },
        "created_at": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "media": {
          "$ref": "#/definitions/models.MediaFileAssoc"
        },
        "media_id": {
          "type": "integer"
        },
        "media_type": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "record_pin": {
          "type": "string"
        },
        "retries": {
          "type": "string"
        },
        "route_0": {
          "type": "integer"
        },
        "route_0_category": {
          "type": "string"
        },
        "route_1": {
          "type": "integer"
        },
        "route_1_category": {
          "type": "string"
        },
        "route_2": {
          "type": "integer"
        },
        "route_2_category": {
          "type": "string"
        },
        "route_3": {
          "type": "integer"
        },
        "route_3_category": {
          "type": "string"
        },
        "route_4": {
          "type": "integer"
        },
        "route_4_category": {
          "type": "string"
        },
        "route_5": {
          "type": "integer"
        },
        "route_5_category": {
          "type": "string"
        },
        "route_6": {
          "type": "integer"
        },
        "route_6_category": {
          "type": "string"
        },
        "route_7": {
          "type": "integer"
        },
        "route_7_category": {
          "type": "string"
        },
        "route_8": {
          "type": "integer"
        },
        "route_8_category": {
          "type": "string"
        },
        "route_9": {
          "type": "integer"
        },
        "route_9_category": {
          "type": "string"
        },
        "route_ast": {
          "type": "integer"
        },
        "route_ast_category": {
          "type": "string"
        },
        "route_timeout": {
          "type": "integer"
        },
        "route_timeout_category": {
          "type": "string"
        },
        "suppress_media": {
          "type": "boolean"
        },
        "timeout": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.MenuDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.Menu"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.MenuListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.Menu"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.Paginator": {
      "type": "object",
      "properties": {
        "limit": {
          "type": "integer"
        },
        "page": {
          "type": "integer"
        },
        "total_pages": {
          "type": "integer"
        },
        "total_rows": {
          "type": "integer"
        }
      }
    },
    "models.PbxConnectorAssoc": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.PbxConnectorAssociation": {
      "type": "object",
      "properties": {
        "caller_id_number": {
          "$ref": "#/definitions/models.PhoneNumberPbxConnector"
        },
        "caller_id_number_other": {
          "type": "string"
        },
        "caller_id_pass_thru": {
          "description": "Caller ID Pass Thru",
          "type": "boolean"
        },
        "created_at": {
          "type": "string"
        },
        "dynamic_call_recording": {
          "type": "boolean"
        },
        "e911_caller_id_pass_thru": {
          "description": "E911 Pass Thru",
          "type": "boolean"
        },
        "emergency_caller_id_number": {
          "$ref": "#/definitions/models.E911RegistrationPbxConnector"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "inbound_call_recording": {
          "type": "boolean"
        },
        "name": {
          "type": "string"
        },
        "outbound_call_recording": {
          "type": "boolean"
        },
        "pbx_manufacturer": {
          "$ref": "#/definitions/models.PbxManufacturer"
        },
        "pbx_manufacturer_other": {
          "type": "string"
        },
        "pbx_model": {
          "$ref": "#/definitions/models.PbxModel"
        },
        "pbx_model_other": {
          "type": "string"
        },
        "pbx_type": {
          "type": "string"
        },
        "site": {
          "$ref": "#/definitions/models.Site"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.PbxConnectorDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.PbxConnectorAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.PbxConnectorListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.PbxConnectorAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.PbxManufacturer": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "title": {
          "type": "string"
        }
      }
    },
    "models.PbxModel": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "title": {
          "type": "string"
        }
      }
    },
    "models.PhoneAssociation": {
      "type": "object",
      "properties": {
        "account": {
          "$ref": "#/definitions/models.AccountDeviceUser"
        },
        "attributes": {
          "type": "array",
          "items": {}
        },
        "call_routing_type": {
          "type": "string"
        },
        "caller_id_prepend": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "e911_registration": {
          "$ref": "#/definitions/models.E911RegistrationAssoc"
        },
        "holiday1": {
          "type": "string"
        },
        "holiday2": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "inbound_cnam_dip": {
          "type": "boolean"
        },
        "main_number": {
          "type": "boolean"
        },
        "main_number_last_updated": {
          "type": "string"
        },
        "outbound_caller_id": {
          "type": "string"
        },
        "pbx_connector": {
          "$ref": "#/definitions/models.PbxConnectorAssoc"
        },
        "phone_number": {
          "type": "string"
        },
        "phone_number_status": {
          "$ref": "#/definitions/models.PhoneNumberStatus"
        },
        "reseller": {
          "$ref": "#/definitions/models.Reseller"
        },
        "routing_to1": {
          "type": "string"
        },
        "routing_to2": {
          "type": "string"
        },
        "sms_routing": {
          "type": "integer"
        },
        "status": {
          "type": "string"
        },
        "t38_faxing": {
          "type": "boolean"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.PhoneAssociationDeviceUser": {
      "type": "object",
      "properties": {
        "attributes": {
          "type": "array",
          "items": {}
        },
        "call_routing_type": {
          "type": "string"
        },
        "caller_id_prepend": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "holiday1": {
          "type": "string"
        },
        "holiday2": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "inbound_cnam_dip": {
          "type": "boolean"
        },
        "main_number": {
          "type": "boolean"
        },
        "main_number_last_updated": {
          "type": "string"
        },
        "outbound_caller_id": {
          "type": "string"
        },
        "phone_number": {
          "type": "string"
        },
        "routing_to1": {
          "type": "string"
        },
        "routing_to2": {
          "type": "string"
        },
        "sms_routing": {
          "type": "integer"
        },
        "status": {
          "type": "string"
        },
        "t38_faxing": {
          "type": "boolean"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.PhoneE911Registration": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "phone_number": {
          "type": "string"
        }
      }
    },
    "models.PhoneNumberDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.PhoneAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.PhoneNumberListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.PhoneAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.PhoneNumberPbxConnector": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "phone_number": {
          "type": "string"
        }
      }
    },
    "models.PhoneNumberStatus": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.Reseller": {
      "type": "object",
      "properties": {
        "address_city": {
          "type": "string"
        },
        "address_country": {
          "type": "string"
        },
        "address_street_1": {
          "type": "string"
        },
        "address_street_2": {
          "type": "string"
        },
        "address_zip": {
          "type": "string"
        },
        "company_name": {
          "type": "string"
        },
        "connectwise_integrated": {
          "type": "boolean"
        },
        "created_at": {
          "type": "string"
        },
        "dba": {
          "type": "string"
        },
        "demo_mode": {
          "type": "boolean"
        },
        "enabled": {
          "type": "boolean"
        },
        "id26": {
          "type": "string"
        }
      }
    },
    "models.Site": {
      "type": "object",
      "properties": {
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.TodRouting": {
      "type": "object",
      "properties": {
        "after_forward_to": {
          "type": "integer"
        },
        "after_forward_to_category": {
          "type": "string"
        },
        "created_at": {
          "type": "string"
        },
        "during_forward_to": {
          "type": "integer"
        },
        "during_forward_to_category": {
          "type": "string"
        },
        "fri_active": {
          "type": "boolean"
        },
        "fri_begin": {
          "type": "string"
        },
        "fri_end": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "mon_active": {
          "type": "boolean"
        },
        "mon_begin": {
          "type": "string"
        },
        "mon_end": {
          "type": "string"
        },
        "name": {
          "type": "string"
        },
        "sat_active": {
          "type": "boolean"
        },
        "sat_begin": {
          "type": "string"
        },
        "sat_end": {
          "type": "string"
        },
        "sun_active": {
          "type": "boolean"
        },
        "sun_begin": {
          "type": "string"
        },
        "sun_end": {
          "type": "string"
        },
        "thu_active": {
          "type": "boolean"
        },
        "thu_begin": {
          "type": "string"
        },
        "thu_end": {
          "type": "string"
        },
        "timezone": {
          "type": "string"
        },
        "tue_active": {
          "type": "boolean"
        },
        "tue_begin": {
          "type": "string"
        },
        "tue_end": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        },
        "wed_active": {
          "type": "boolean"
        },
        "wed_begin": {
          "type": "string"
        },
        "wed_end": {
          "type": "string"
        }
      }
    },
    "models.TodRoutingDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.TodRouting"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.TodRoutingListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.TodRouting"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.UserAccount": {
      "type": "object",
      "properties": {
        "first_name": {
          "type": "string"
        },
        "id": {
          "type": "string"
        },
        "last_name": {
          "type": "string"
        }
      }
    },
    "models.VirtualExtension": {
      "type": "object",
      "required": [
        "extension",
        "name",
        "route_to_category"
      ],
      "properties": {
        "account_id": {
          "type": "integer"
        },
        "created_at": {
          "type": "string"
        },
        "extension": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "inbound_call_recording": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        },
        "prepend_caller_id": {
          "type": "string"
        },
        "reset_caller_id": {
          "type": "boolean"
        },
        "route_to": {
          "type": "integer"
        },
        "route_to_category": {
          "type": "string"
        },
        "secondary_route_to": {
          "type": "integer"
        },
        "secondary_route_to_category": {
          "type": "string"
        },
        "seconds_to_ring": {
          "type": "integer"
        },
        "updated_at": {
          "type": "string"
        }
      }
    },
    "models.VirtualExtensionAssoc": {
      "type": "object",
      "properties": {
        "extension": {
          "type": "string"
        },
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.VirtualExtensionDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.VirtualExtension"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.VirtualExtensionListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.VirtualExtension"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.VoicemailBox": {
      "type": "object",
      "properties": {
        "additional_emails": {
          "type": "string"
        },
        "device_user_id": {
          "type": "integer"
        },
        "id": {
          "type": "integer"
        },
        "name": {
          "type": "string"
        }
      }
    },
    "models.VoicemailBoxAssociation": {
      "type": "object",
      "properties": {
        "additional_emails": {
          "type": "string"
        },
        "check_if_owner": {
          "type": "boolean"
        },
        "created_at": {
          "type": "string"
        },
        "delete_after_notify": {
          "type": "boolean"
        },
        "device_user_id": {
          "type": "integer"
        },
        "enabled": {
          "type": "boolean"
        },
        "id": {
          "type": "integer"
        },
        "id26": {
          "type": "string"
        },
        "is_setup": {
          "type": "boolean"
        },
        "mailbox": {
          "type": "string"
        },
        "media": {
          "$ref": "#/definitions/models.MediaFile"
        },
        "name": {
          "type": "string"
        },
        "require_pin": {
          "type": "boolean"
        },
        "send_to_boomea": {
          "type": "boolean"
        },
        "skip_greeting": {
          "type": "boolean"
        },
        "skip_instructions": {
          "type": "boolean"
        },
        "timezone": {
          "type": "string"
        },
        "unavailable_media_id": {
          "type": "integer"
        },
        "unavailable_media_type": {
          "type": "string"
        },
        "updated_at": {
          "type": "string"
        },
        "voiceaxis_id": {
          "type": "boolean"
        },
        "voip_id": {
          "type": "string"
        }
      }
    },
    "models.VoicemailBoxDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "$ref": "#/definitions/models.VoicemailBoxAssociation"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    },
    "models.VoicemailBoxListDoc": {
      "type": "object",
      "properties": {
        "code": {
          "type": "integer"
        },
        "data": {
          "type": "array",
          "items": {
            "$ref": "#/definitions/models.VoicemailBoxAssociation"
          }
        },
        "paginator": {
          "$ref": "#/definitions/models.Paginator"
        },
        "request_id": {
          "type": "string"
        },
        "status": {
          "type": "string"
        }
      }
    }
  },
  "tags": [
    {
      "description": "Titan API uses OAuth 2.0 (Open Authorization) to access to the APIs.  \nIt is implemented with Google's Go Language OAuth2 package: https://pkg.go.dev/golang.org/x/oauth2  \n\nTitan supports 3 Grant Types:  \n\n<ins>Client Credentials Grant</ins>  \nUsed for server-to-server access.  \n\n<ins>Authorization Code Grant</ins>  \nUsed for web apps that execute from a server.  \n\n<ins>Authorization Code Grant with Proof Key for Code Exchange (PKCE)</ins>  \nUsed for single page apps (SPAs) running from a browser.  \n\n## Client Credentials Grant\nTo use this flow:\n1. Log into the portal and Navigate to your Account Page.\n2. From the right handle menu, select \"API Server Access\".\n3. Click the \"ADD CLIENT\" button.\n4. Enter a unique client id and check the VOIP checkbox, then click SAVE.\n5. In the list of API Clients, click the View Secret icon to the right of the client.\n\n6. Make an API call using your preferred method to the following API endpoint.\n\t- cURL is used in this example\n\t- replace your client id and secret in the example below\n\n```\ncurl -X POST \\\nhttps://api.titan.host/api/v2/credential/token \\\n-H 'content-type: application/x-www-form-urlencoded' \\\n-d 'grant_type=client_credentials&client_id=<<<your client id>>>&client_secret=<<<your secret>>>&scope=voip'\n```\n\nThe return payload will appear as:\n\n```\n{\n  \"ClientID\": \"<<<your client id>>>\",\n  \"UserID\": \"<<<your user id>>>\",\n  \"RedirectURI\": \"\",\n  \"Scope\": \"voip\",\n  \"Code\": \"\",\n  \"CodeChallenge\": \"\",\n  \"CodeChallengeMethod\": \"\",\n  \"CodeCreateAt\": \"0001-01-01T00:00:00Z\",\n  \"CodeExpiresIn\": 0,\n  \"Access\": \"<<<your api token>>>\",\n  \"AccessCreateAt\": \"2022-03-02T21:38:35.440343208Z\",\n  \"AccessExpiresIn\": 7200,\n  \"Refresh\": \"\",\n  \"RefreshCreateAt\": \"2022-03-02T21:38:35.440345043Z\",\n  \"RefreshExpiresIn\": 259200\n}\n```\n\n7. Make an API call with the new token:\n\n```\ncurl -H 'Accept: application/json' \\\n-H \"Authorization: Bearer <<<your api token>>>\" \\\nhttps://api.titan.host/api/v2/account_settings\n```\n8. Your token is good for 2 hrs.  After that you need to get a new token by re-running the same api in steps 6.\n\n## Authorization Code Grant\nTo use this flow:\n1. Log into the portal and Navigate to your Account Page.\n2. From the right handle menu, select \"API User Access\".\n3. Click the \"ADD CLIENT\" button.\n4. Enter  \n\tA. a unique client id  \n\tB. callback URL to you application, for example: https://exmple.com/callback  \n\tC. check the VOIP checkbox, then  \n\tD. click SAVE.  \n5. In the list of API Clients, click the View Secret icon to the right of the client.\n6. Most programming languages provide a package for interfacing with a backend OAuth system like Titan.  The following instructions give you an idea of the flow demonstrated with cURL.  Make a call to the following endpoint to redirect you to the Titan login page\n\t- replace your client id in the example below\n\t- replace your applications call back URL in the example below\n\t- replace your state code in the example below, but this is optional\n\t- NOTE that line feeds have been added for clarity, and should be removed when running cURL\n\n```\ncurl -v 'https://api.titan.host/api/v2/code/authorize?\nclient_id=<<<your client id>>>&\nredirect_uri=http%3A%2F%2Flocalhost%3A3000%2Fdashboard&\nresponse_type=code&\nstate=<<<your state code>>>&\nscope=voip'\n```\n\n7. Titan will prompt the user for their portal account username and password.\n\n![Login Page](https://docs.titan.host/auth_page1.png)\n\n8. Titan will ask the user for authorization to gain access to the VOIP account level API services.\n\n![Scope Page](https://docs.titan.host/auth_page2.png)\n\n9. If the user entered valid credentials and allowed access to the requested scopes setup in the client id, then the user will be redirected back to the application via the callback URL defined in the client setup.  The call back will include a code query string that is used to exchange for a token, and the optional state that can be used in the application to mitigate CSRF attacks.  For example:\n\n```\nhttp://localhost:3000/dashboard?code=YTNHUDBLODITYWU2NC0ZMGFJLTG3NTUTMMFIYZG1YTYXYZAB&state=somestate\n```\n\n10. exchange the code for an access token using the following API call:\n\t- replace your client id and secret in the example below\n\t- replace your code above in the example below\n\t- replace your applications call back URL in the example below\n\t- NOTE that line feeds have been added for clarity, and should be removed when running cURL\n\n```\ncurl -v -X POST\n-H 'cache-control: no-cache'\n-H \"Content-Type: application/x-www-form-urlencoded\"\n-u <<<client id>>>:<<<secret>>>\n-d \"code=YTNHUDBLODITYWU2NC0ZMGFJLTG3NTUTMMFIYZG1YTYXYZAB&\ngrant_type=authorization_code&\nredirect_uri=http%3A%2F%2Flocalhost%3A3000%2Fdashboard\"\nhttps://api.titan.host/api/v2/code/token\n```\n\nthe expected response will be as follows:\n```\n{\n  \"access_token\":\"QWERTGZMNDCTMTU4OC0ZYJGXLTHINJYTNMEYZGVKMTNQWERT\",\n  \"client_id\":\"<<<client id>>>\",\n  \"code\":\"\",\n  \"expires_in\":7200,\n  \"redirect_url\":\"http://localhost:3000/dashboard\",\n  \"refresh_token\":\"QWERTTE2MDETMGNJMS01M2RILWEXNDUTNTHKODIWMZHQWERT\",\n  \"scope\":\"VOIP\",\n  \"token_type\":\"Bearer\",\n  \"user_id\":\"<<<userid>>>\"\n}\n```\n\n11. Make an API call with the new token:\n\t- replace your Bearer code with the access_token above in the example below\n\t- NOTE that line feeds have been added for clarity, and should be removed when running cURL\n\n```\ncurl -v\n-H 'cache-control: no-cache'\n-H 'Accept: application/json'\n-H \"Authorization: Bearer <<<your access_token>>>\"\nhttps://api.titan.host/api/v2/account_settings\n```\n## Authorization Code Grant with Proof Key for Code Exchange (PKCE)\nTitan provides PKCE option for applications that should not store a client secret, such as native or single-page apps.\n\nIt is recommended to use the appropriate package for your programming language to handle the details of creating the challange code.\n\n1. the authorize endpoint is different from above\n\n```\ncurl -v\n-H 'cache-control: no-cache'\n-H 'content-type: application/x-www-form-urlencoded'\n'https://api.titan.host/api/v2/code/authorize?\nclient_id=<<<client id>>>&\nredirect_uri=http%3A%2F%2Flocalhost%3A3000%2Fdashboard&\nresponse_type=code&\ncode_challenge=<<<challange code>>>&\ncode_challenge_method=plain'\n```\n",
      "name": "Authentication"
    },
    {
      "description": "Titan uses the following convention when returning a response:\n\n```\n{\n  \"code\": 200,\n  \"data\": {\n    <<<your data here>>>\n  },\n  \"request_id\": \"Hv3tbeWqx4ezkcbZxypJsucbHZ\",\n  \"status\": \"success\"\n}\n```\nCode is the HTTP response.  \nData is the payload specific to the endpoint.  \nIf your data is one single item it will be enclosed in {}.  \nIf your data is a list of items it will be enclosed in an array [{},{},...]  \nRequestId is unique to each request.  \nStatus is a code indicating success or error.  \n",
      "name": "Endpoint Payload"
    },
    {
      "description": "When calling an API endpoint that returns a list of items, only the first 10 records are returned.  \nA response payload will include pagination information:\n```\n{\n  \"code\": 200,\n  \"data\": [<<<your data here>>>],\n  \"paginator\": {\n    \"limit\": 10,\n    \"page\": 1,\n    \"total_rows\": 1,\n    \"total_pages\": 1\n  },\n  \"request_id\": \"Hv3tbeWqx4ezkcbZxypJsucbHZ\",\n  \"status\": \"success\"\n}\n```\nTo get the next set of records, call the endpoint again and pass in the page query string\n```\n?page=2\n```\nYou can adjust this limit by passing in a new limit in the endpoint query string\n```\n?limit=100\n```\n",
      "name": "Pagination"
    },
    {
      "description": "Rate limiting has been implemented to prevent abuse of the system.  \nRate limiting is implemented using the generic cell rate algorithm to limit access to resource endpoints.  \nThe system limits access to an endpoint up to 20 requests per minute with bursts of up to 5 additional requests.  \nIf you need higher limits, please contact your administrator.  \nRate Limit information is returned in each API response as headers.  \n```\n< X-Ratelimit-Limit: 6\n< X-Ratelimit-Remaining: 5\n< X-Ratelimit-Reset: 3\n```\nWhen a limit has been exceeded, you will get a response that looks like this:\n```\n< HTTP/1.1 429 Too Many Requests\n< X-Ratelimit-Limit: 6\n< X-Ratelimit-Remaining: 0\n< X-Ratelimit-Reset: 18\n\nlimit exceeded\n```\n",
      "name": "Rate Limiting"
    },
    {
      "description": "VoIP endpoints provide GET all and GET single access to your VoIP data in the portal for a single account.\nThe GET all follows this standard convention:\n```\ncurl https://api.titan.host/api/v2/phonenumbers\n```\n\nAnd the GET single follows this standard convention:\n```\ncurl https://api.titan.host/api/v2/phonenumbers/4567\nor\ncurl https://api.titan.host/api/v2/phonenumbers/tyj987sdewdrf56lko09345fgb\n```\n\nIn the example above, the numeric id of the record is provided.\nIn the 2nd example, the id26 of the record is provided.\nBoth result in the same response.\n",
      "name": "VoIP"
    },
    {
      "name": "VoIP Account Settings"
    },
    {
      "name": "VoIP Phone Numbers"
    },
    {
      "name": "VoIP E911 Registration"
    },
    {
      "name": "VoIP PBX Connector"
    },
    {
      "name": "VoIP Device Users"
    },
    {
      "name": "VoIP Devices"
    },
    {
      "name": "VoIP Virtual Extensions"
    },
    {
      "name": "VoIP Voicemail Boxes"
    },
    {
      "name": "VoIP Fax Boxes"
    },
    {
      "name": "VoIP Time Of Day Routing"
    },
    {
      "name": "VoIP Menus"
    },
    {
      "name": "VoIP Groups"
    },
    {
      "name": "VoIP Media"
    },
    {
      "name": "VoIP Conferences"
    },
    {
      "name": "VoIP Holiday Routing"
    },
    {
      "name": "VoIP Blacklist"
    },
    {
      "name": "VoIP DISA"
    },
    {
      "name": "VoIP Call Center Queues"
    }
  ]
}
