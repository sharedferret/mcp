# Tool Selection Analysis Setup

**Setup completed:** 2025-10-02 10:19:15  
**Tool count:** 147  
**Database setup time:** 2.6624024s  

---

# Tool Selection Analysis Results

**Analysis Date:** 2025-10-02 10:19:15  
**Tool count:** 147  

## Table of Contents

- [Test 1: azmcp_foundry_agents_connect](#test-1)
- [Test 2: azmcp_foundry_agents_evaluate](#test-2)
- [Test 3: azmcp_foundry_agents_query-and-evaluate](#test-3)
- [Test 4: azmcp_foundry_knowledge_index_list](#test-4)
- [Test 5: azmcp_foundry_knowledge_index_list](#test-5)
- [Test 6: azmcp_foundry_knowledge_index_schema](#test-6)
- [Test 7: azmcp_foundry_knowledge_index_schema](#test-7)
- [Test 8: azmcp_foundry_models_deploy](#test-8)
- [Test 9: azmcp_foundry_models_deployments_list](#test-9)
- [Test 10: azmcp_foundry_models_deployments_list](#test-10)
- [Test 11: azmcp_foundry_models_list](#test-11)
- [Test 12: azmcp_foundry_models_list](#test-12)
- [Test 13: azmcp_foundry_openai_create-completion](#test-13)
- [Test 14: azmcp_search_index_get](#test-14)
- [Test 15: azmcp_search_index_get](#test-15)
- [Test 16: azmcp_search_index_get](#test-16)
- [Test 17: azmcp_search_index_query](#test-17)
- [Test 18: azmcp_search_service_list](#test-18)
- [Test 19: azmcp_search_service_list](#test-19)
- [Test 20: azmcp_search_service_list](#test-20)
- [Test 21: azmcp_speech_stt_recognize](#test-21)
- [Test 22: azmcp_speech_stt_recognize](#test-22)
- [Test 23: azmcp_speech_stt_recognize](#test-23)
- [Test 24: azmcp_speech_stt_recognize](#test-24)
- [Test 25: azmcp_speech_stt_recognize](#test-25)
- [Test 26: azmcp_speech_stt_recognize](#test-26)
- [Test 27: azmcp_speech_stt_recognize](#test-27)
- [Test 28: azmcp_speech_stt_recognize](#test-28)
- [Test 29: azmcp_speech_stt_recognize](#test-29)
- [Test 30: azmcp_speech_stt_recognize](#test-30)
- [Test 31: azmcp_appconfig_account_list](#test-31)
- [Test 32: azmcp_appconfig_account_list](#test-32)
- [Test 33: azmcp_appconfig_account_list](#test-33)
- [Test 34: azmcp_appconfig_kv_delete](#test-34)
- [Test 35: azmcp_appconfig_kv_get](#test-35)
- [Test 36: azmcp_appconfig_kv_get](#test-36)
- [Test 37: azmcp_appconfig_kv_get](#test-37)
- [Test 38: azmcp_appconfig_kv_get](#test-38)
- [Test 39: azmcp_appconfig_kv_lock_set](#test-39)
- [Test 40: azmcp_appconfig_kv_lock_set](#test-40)
- [Test 41: azmcp_appconfig_kv_set](#test-41)
- [Test 42: azmcp_applens_resource_diagnose](#test-42)
- [Test 43: azmcp_applens_resource_diagnose](#test-43)
- [Test 44: azmcp_applens_resource_diagnose](#test-44)
- [Test 45: azmcp_appservice_database_add](#test-45)
- [Test 46: azmcp_appservice_database_add](#test-46)
- [Test 47: azmcp_appservice_database_add](#test-47)
- [Test 48: azmcp_appservice_database_add](#test-48)
- [Test 49: azmcp_appservice_database_add](#test-49)
- [Test 50: azmcp_appservice_database_add](#test-50)
- [Test 51: azmcp_appservice_database_add](#test-51)
- [Test 52: azmcp_appservice_database_add](#test-52)
- [Test 53: azmcp_appservice_database_add](#test-53)
- [Test 54: azmcp_applicationinsights_recommendation_list](#test-54)
- [Test 55: azmcp_applicationinsights_recommendation_list](#test-55)
- [Test 56: azmcp_applicationinsights_recommendation_list](#test-56)
- [Test 57: azmcp_applicationinsights_recommendation_list](#test-57)
- [Test 58: azmcp_acr_registry_list](#test-58)
- [Test 59: azmcp_acr_registry_list](#test-59)
- [Test 60: azmcp_acr_registry_list](#test-60)
- [Test 61: azmcp_acr_registry_list](#test-61)
- [Test 62: azmcp_acr_registry_list](#test-62)
- [Test 63: azmcp_acr_registry_repository_list](#test-63)
- [Test 64: azmcp_acr_registry_repository_list](#test-64)
- [Test 65: azmcp_acr_registry_repository_list](#test-65)
- [Test 66: azmcp_acr_registry_repository_list](#test-66)
- [Test 67: azmcp_cosmos_account_list](#test-67)
- [Test 68: azmcp_cosmos_account_list](#test-68)
- [Test 69: azmcp_cosmos_account_list](#test-69)
- [Test 70: azmcp_cosmos_database_container_item_query](#test-70)
- [Test 71: azmcp_cosmos_database_container_list](#test-71)
- [Test 72: azmcp_cosmos_database_container_list](#test-72)
- [Test 73: azmcp_cosmos_database_list](#test-73)
- [Test 74: azmcp_cosmos_database_list](#test-74)
- [Test 75: azmcp_kusto_cluster_get](#test-75)
- [Test 76: azmcp_kusto_cluster_list](#test-76)
- [Test 77: azmcp_kusto_cluster_list](#test-77)
- [Test 78: azmcp_kusto_cluster_list](#test-78)
- [Test 79: azmcp_kusto_database_list](#test-79)
- [Test 80: azmcp_kusto_database_list](#test-80)
- [Test 81: azmcp_kusto_query](#test-81)
- [Test 82: azmcp_kusto_sample](#test-82)
- [Test 83: azmcp_kusto_table_list](#test-83)
- [Test 84: azmcp_kusto_table_list](#test-84)
- [Test 85: azmcp_kusto_table_schema](#test-85)
- [Test 86: azmcp_mysql_database_list](#test-86)
- [Test 87: azmcp_mysql_database_list](#test-87)
- [Test 88: azmcp_mysql_database_query](#test-88)
- [Test 89: azmcp_mysql_server_config_get](#test-89)
- [Test 90: azmcp_mysql_server_list](#test-90)
- [Test 91: azmcp_mysql_server_list](#test-91)
- [Test 92: azmcp_mysql_server_list](#test-92)
- [Test 93: azmcp_mysql_server_param_get](#test-93)
- [Test 94: azmcp_mysql_server_param_set](#test-94)
- [Test 95: azmcp_mysql_table_list](#test-95)
- [Test 96: azmcp_mysql_table_list](#test-96)
- [Test 97: azmcp_mysql_table_schema_get](#test-97)
- [Test 98: azmcp_postgres_database_list](#test-98)
- [Test 99: azmcp_postgres_database_list](#test-99)
- [Test 100: azmcp_postgres_database_query](#test-100)
- [Test 101: azmcp_postgres_server_config_get](#test-101)
- [Test 102: azmcp_postgres_server_list](#test-102)
- [Test 103: azmcp_postgres_server_list](#test-103)
- [Test 104: azmcp_postgres_server_list](#test-104)
- [Test 105: azmcp_postgres_server_param_get](#test-105)
- [Test 106: azmcp_postgres_server_param_set](#test-106)
- [Test 107: azmcp_postgres_table_list](#test-107)
- [Test 108: azmcp_postgres_table_list](#test-108)
- [Test 109: azmcp_postgres_table_schema_get](#test-109)
- [Test 110: azmcp_deploy_app_logs_get](#test-110)
- [Test 111: azmcp_deploy_architecture_diagram_generate](#test-111)
- [Test 112: azmcp_deploy_iac_rules_get](#test-112)
- [Test 113: azmcp_deploy_pipeline_guidance_get](#test-113)
- [Test 114: azmcp_deploy_plan_get](#test-114)
- [Test 115: azmcp_eventgrid_events_publish](#test-115)
- [Test 116: azmcp_eventgrid_events_publish](#test-116)
- [Test 117: azmcp_eventgrid_events_publish](#test-117)
- [Test 118: azmcp_eventgrid_topic_list](#test-118)
- [Test 119: azmcp_eventgrid_topic_list](#test-119)
- [Test 120: azmcp_eventgrid_topic_list](#test-120)
- [Test 121: azmcp_eventgrid_topic_list](#test-121)
- [Test 122: azmcp_eventgrid_subscription_list](#test-122)
- [Test 123: azmcp_eventgrid_subscription_list](#test-123)
- [Test 124: azmcp_eventgrid_subscription_list](#test-124)
- [Test 125: azmcp_eventgrid_subscription_list](#test-125)
- [Test 126: azmcp_eventgrid_subscription_list](#test-126)
- [Test 127: azmcp_eventgrid_subscription_list](#test-127)
- [Test 128: azmcp_eventgrid_subscription_list](#test-128)
- [Test 129: azmcp_eventhubs_namespace_get](#test-129)
- [Test 130: azmcp_eventhubs_namespace_get](#test-130)
- [Test 131: azmcp_functionapp_get](#test-131)
- [Test 132: azmcp_functionapp_get](#test-132)
- [Test 133: azmcp_functionapp_get](#test-133)
- [Test 134: azmcp_functionapp_get](#test-134)
- [Test 135: azmcp_functionapp_get](#test-135)
- [Test 136: azmcp_functionapp_get](#test-136)
- [Test 137: azmcp_functionapp_get](#test-137)
- [Test 138: azmcp_functionapp_get](#test-138)
- [Test 139: azmcp_functionapp_get](#test-139)
- [Test 140: azmcp_functionapp_get](#test-140)
- [Test 141: azmcp_functionapp_get](#test-141)
- [Test 142: azmcp_functionapp_get](#test-142)
- [Test 143: azmcp_keyvault_admin_settings_get](#test-143)
- [Test 144: azmcp_keyvault_admin_settings_get](#test-144)
- [Test 145: azmcp_keyvault_admin_settings_get](#test-145)
- [Test 146: azmcp_keyvault_certificate_create](#test-146)
- [Test 147: azmcp_keyvault_certificate_create](#test-147)
- [Test 148: azmcp_keyvault_certificate_create](#test-148)
- [Test 149: azmcp_keyvault_certificate_create](#test-149)
- [Test 150: azmcp_keyvault_certificate_create](#test-150)
- [Test 151: azmcp_keyvault_certificate_get](#test-151)
- [Test 152: azmcp_keyvault_certificate_get](#test-152)
- [Test 153: azmcp_keyvault_certificate_get](#test-153)
- [Test 154: azmcp_keyvault_certificate_get](#test-154)
- [Test 155: azmcp_keyvault_certificate_get](#test-155)
- [Test 156: azmcp_keyvault_certificate_import](#test-156)
- [Test 157: azmcp_keyvault_certificate_import](#test-157)
- [Test 158: azmcp_keyvault_certificate_import](#test-158)
- [Test 159: azmcp_keyvault_certificate_import](#test-159)
- [Test 160: azmcp_keyvault_certificate_import](#test-160)
- [Test 161: azmcp_keyvault_certificate_list](#test-161)
- [Test 162: azmcp_keyvault_certificate_list](#test-162)
- [Test 163: azmcp_keyvault_certificate_list](#test-163)
- [Test 164: azmcp_keyvault_certificate_list](#test-164)
- [Test 165: azmcp_keyvault_certificate_list](#test-165)
- [Test 166: azmcp_keyvault_certificate_list](#test-166)
- [Test 167: azmcp_keyvault_key_create](#test-167)
- [Test 168: azmcp_keyvault_key_create](#test-168)
- [Test 169: azmcp_keyvault_key_create](#test-169)
- [Test 170: azmcp_keyvault_key_create](#test-170)
- [Test 171: azmcp_keyvault_key_create](#test-171)
- [Test 172: azmcp_keyvault_key_get](#test-172)
- [Test 173: azmcp_keyvault_key_get](#test-173)
- [Test 174: azmcp_keyvault_key_get](#test-174)
- [Test 175: azmcp_keyvault_key_get](#test-175)
- [Test 176: azmcp_keyvault_key_get](#test-176)
- [Test 177: azmcp_keyvault_key_list](#test-177)
- [Test 178: azmcp_keyvault_key_list](#test-178)
- [Test 179: azmcp_keyvault_key_list](#test-179)
- [Test 180: azmcp_keyvault_key_list](#test-180)
- [Test 181: azmcp_keyvault_key_list](#test-181)
- [Test 182: azmcp_keyvault_key_list](#test-182)
- [Test 183: azmcp_keyvault_secret_create](#test-183)
- [Test 184: azmcp_keyvault_secret_create](#test-184)
- [Test 185: azmcp_keyvault_secret_create](#test-185)
- [Test 186: azmcp_keyvault_secret_create](#test-186)
- [Test 187: azmcp_keyvault_secret_create](#test-187)
- [Test 188: azmcp_keyvault_secret_get](#test-188)
- [Test 189: azmcp_keyvault_secret_get](#test-189)
- [Test 190: azmcp_keyvault_secret_get](#test-190)
- [Test 191: azmcp_keyvault_secret_get](#test-191)
- [Test 192: azmcp_keyvault_secret_get](#test-192)
- [Test 193: azmcp_keyvault_secret_list](#test-193)
- [Test 194: azmcp_keyvault_secret_list](#test-194)
- [Test 195: azmcp_keyvault_secret_list](#test-195)
- [Test 196: azmcp_keyvault_secret_list](#test-196)
- [Test 197: azmcp_keyvault_secret_list](#test-197)
- [Test 198: azmcp_keyvault_secret_list](#test-198)
- [Test 199: azmcp_aks_cluster_get](#test-199)
- [Test 200: azmcp_aks_cluster_get](#test-200)
- [Test 201: azmcp_aks_cluster_get](#test-201)
- [Test 202: azmcp_aks_cluster_get](#test-202)
- [Test 203: azmcp_aks_cluster_list](#test-203)
- [Test 204: azmcp_aks_cluster_list](#test-204)
- [Test 205: azmcp_aks_cluster_list](#test-205)
- [Test 206: azmcp_aks_nodepool_get](#test-206)
- [Test 207: azmcp_aks_nodepool_get](#test-207)
- [Test 208: azmcp_aks_nodepool_get](#test-208)
- [Test 209: azmcp_aks_nodepool_list](#test-209)
- [Test 210: azmcp_aks_nodepool_list](#test-210)
- [Test 211: azmcp_aks_nodepool_list](#test-211)
- [Test 212: azmcp_loadtesting_test_create](#test-212)
- [Test 213: azmcp_loadtesting_test_get](#test-213)
- [Test 214: azmcp_loadtesting_testresource_create](#test-214)
- [Test 215: azmcp_loadtesting_testresource_list](#test-215)
- [Test 216: azmcp_loadtesting_testrun_create](#test-216)
- [Test 217: azmcp_loadtesting_testrun_get](#test-217)
- [Test 218: azmcp_loadtesting_testrun_list](#test-218)
- [Test 219: azmcp_loadtesting_testrun_update](#test-219)
- [Test 220: azmcp_grafana_list](#test-220)
- [Test 221: azmcp_azuremanagedlustre_filesystem_list](#test-221)
- [Test 222: azmcp_azuremanagedlustre_filesystem_list](#test-222)
- [Test 223: azmcp_azuremanagedlustre_filesystem_required-subnet-size](#test-223)
- [Test 224: azmcp_azuremanagedlustre_filesystem_sku_get](#test-224)
- [Test 225: azmcp_marketplace_product_get](#test-225)
- [Test 226: azmcp_marketplace_product_list](#test-226)
- [Test 227: azmcp_marketplace_product_list](#test-227)
- [Test 228: azmcp_get_bestpractices_get](#test-228)
- [Test 229: azmcp_get_bestpractices_get](#test-229)
- [Test 230: azmcp_get_bestpractices_get](#test-230)
- [Test 231: azmcp_get_bestpractices_get](#test-231)
- [Test 232: azmcp_get_bestpractices_get](#test-232)
- [Test 233: azmcp_get_bestpractices_get](#test-233)
- [Test 234: azmcp_get_bestpractices_get](#test-234)
- [Test 235: azmcp_get_bestpractices_get](#test-235)
- [Test 236: azmcp_monitor_healthmodels_entity_gethealth](#test-236)
- [Test 237: azmcp_monitor_metrics_definitions](#test-237)
- [Test 238: azmcp_monitor_metrics_definitions](#test-238)
- [Test 239: azmcp_monitor_metrics_definitions](#test-239)
- [Test 240: azmcp_monitor_metrics_query](#test-240)
- [Test 241: azmcp_monitor_metrics_query](#test-241)
- [Test 242: azmcp_monitor_metrics_query](#test-242)
- [Test 243: azmcp_monitor_metrics_query](#test-243)
- [Test 244: azmcp_monitor_metrics_query](#test-244)
- [Test 245: azmcp_monitor_metrics_query](#test-245)
- [Test 246: azmcp_monitor_resource_log_query](#test-246)
- [Test 247: azmcp_monitor_table_list](#test-247)
- [Test 248: azmcp_monitor_table_list](#test-248)
- [Test 249: azmcp_monitor_table_type_list](#test-249)
- [Test 250: azmcp_monitor_table_type_list](#test-250)
- [Test 251: azmcp_monitor_workspace_list](#test-251)
- [Test 252: azmcp_monitor_workspace_list](#test-252)
- [Test 253: azmcp_monitor_workspace_list](#test-253)
- [Test 254: azmcp_monitor_workspace_log_query](#test-254)
- [Test 255: azmcp_datadog_monitoredresources_list](#test-255)
- [Test 256: azmcp_datadog_monitoredresources_list](#test-256)
- [Test 257: azmcp_extension_azqr](#test-257)
- [Test 258: azmcp_extension_azqr](#test-258)
- [Test 259: azmcp_extension_azqr](#test-259)
- [Test 260: azmcp_quota_region_availability_list](#test-260)
- [Test 261: azmcp_quota_usage_check](#test-261)
- [Test 262: azmcp_role_assignment_list](#test-262)
- [Test 263: azmcp_role_assignment_list](#test-263)
- [Test 264: azmcp_redis_cache_accesspolicy_list](#test-264)
- [Test 265: azmcp_redis_cache_accesspolicy_list](#test-265)
- [Test 266: azmcp_redis_list](#test-266)
- [Test 267: azmcp_redis_list](#test-267)
- [Test 268: azmcp_redis_list](#test-268)
- [Test 269: azmcp_redis_cluster_database_list](#test-269)
- [Test 270: azmcp_redis_cluster_database_list](#test-270)
- [Test 271: azmcp_group_list](#test-271)
- [Test 272: azmcp_group_list](#test-272)
- [Test 273: azmcp_group_list](#test-273)
- [Test 274: azmcp_resourcehealth_availability-status_get](#test-274)
- [Test 275: azmcp_resourcehealth_availability-status_get](#test-275)
- [Test 276: azmcp_resourcehealth_availability-status_get](#test-276)
- [Test 277: azmcp_resourcehealth_availability-status_list](#test-277)
- [Test 278: azmcp_resourcehealth_availability-status_list](#test-278)
- [Test 279: azmcp_resourcehealth_availability-status_list](#test-279)
- [Test 280: azmcp_resourcehealth_service-health-events_list](#test-280)
- [Test 281: azmcp_resourcehealth_service-health-events_list](#test-281)
- [Test 282: azmcp_resourcehealth_service-health-events_list](#test-282)
- [Test 283: azmcp_resourcehealth_service-health-events_list](#test-283)
- [Test 284: azmcp_resourcehealth_service-health-events_list](#test-284)
- [Test 285: azmcp_servicebus_queue_details](#test-285)
- [Test 286: azmcp_servicebus_topic_details](#test-286)
- [Test 287: azmcp_servicebus_topic_subscription_details](#test-287)
- [Test 288: azmcp_sql_db_create](#test-288)
- [Test 289: azmcp_sql_db_create](#test-289)
- [Test 290: azmcp_sql_db_create](#test-290)
- [Test 291: azmcp_sql_db_delete](#test-291)
- [Test 292: azmcp_sql_db_delete](#test-292)
- [Test 293: azmcp_sql_db_delete](#test-293)
- [Test 294: azmcp_sql_db_list](#test-294)
- [Test 295: azmcp_sql_db_list](#test-295)
- [Test 296: azmcp_sql_db_rename](#test-296)
- [Test 297: azmcp_sql_db_rename](#test-297)
- [Test 298: azmcp_sql_db_show](#test-298)
- [Test 299: azmcp_sql_db_show](#test-299)
- [Test 300: azmcp_sql_db_update](#test-300)
- [Test 301: azmcp_sql_db_update](#test-301)
- [Test 302: azmcp_sql_elastic-pool_list](#test-302)
- [Test 303: azmcp_sql_elastic-pool_list](#test-303)
- [Test 304: azmcp_sql_elastic-pool_list](#test-304)
- [Test 305: azmcp_sql_server_create](#test-305)
- [Test 306: azmcp_sql_server_create](#test-306)
- [Test 307: azmcp_sql_server_create](#test-307)
- [Test 308: azmcp_sql_server_delete](#test-308)
- [Test 309: azmcp_sql_server_delete](#test-309)
- [Test 310: azmcp_sql_server_delete](#test-310)
- [Test 311: azmcp_sql_server_entra-admin_list](#test-311)
- [Test 312: azmcp_sql_server_entra-admin_list](#test-312)
- [Test 313: azmcp_sql_server_entra-admin_list](#test-313)
- [Test 314: azmcp_sql_server_firewall-rule_create](#test-314)
- [Test 315: azmcp_sql_server_firewall-rule_create](#test-315)
- [Test 316: azmcp_sql_server_firewall-rule_create](#test-316)
- [Test 317: azmcp_sql_server_firewall-rule_delete](#test-317)
- [Test 318: azmcp_sql_server_firewall-rule_delete](#test-318)
- [Test 319: azmcp_sql_server_firewall-rule_delete](#test-319)
- [Test 320: azmcp_sql_server_firewall-rule_list](#test-320)
- [Test 321: azmcp_sql_server_firewall-rule_list](#test-321)
- [Test 322: azmcp_sql_server_firewall-rule_list](#test-322)
- [Test 323: azmcp_sql_server_list](#test-323)
- [Test 324: azmcp_sql_server_list](#test-324)
- [Test 325: azmcp_sql_server_show](#test-325)
- [Test 326: azmcp_sql_server_show](#test-326)
- [Test 327: azmcp_sql_server_show](#test-327)
- [Test 328: azmcp_storage_account_create](#test-328)
- [Test 329: azmcp_storage_account_create](#test-329)
- [Test 330: azmcp_storage_account_create](#test-330)
- [Test 331: azmcp_storage_account_get](#test-331)
- [Test 332: azmcp_storage_account_get](#test-332)
- [Test 333: azmcp_storage_account_get](#test-333)
- [Test 334: azmcp_storage_account_get](#test-334)
- [Test 335: azmcp_storage_account_get](#test-335)
- [Test 336: azmcp_storage_blob_container_create](#test-336)
- [Test 337: azmcp_storage_blob_container_create](#test-337)
- [Test 338: azmcp_storage_blob_container_create](#test-338)
- [Test 339: azmcp_storage_blob_container_get](#test-339)
- [Test 340: azmcp_storage_blob_container_get](#test-340)
- [Test 341: azmcp_storage_blob_container_get](#test-341)
- [Test 342: azmcp_storage_blob_get](#test-342)
- [Test 343: azmcp_storage_blob_get](#test-343)
- [Test 344: azmcp_storage_blob_get](#test-344)
- [Test 345: azmcp_storage_blob_get](#test-345)
- [Test 346: azmcp_storage_blob_upload](#test-346)
- [Test 347: azmcp_subscription_list](#test-347)
- [Test 348: azmcp_subscription_list](#test-348)
- [Test 349: azmcp_subscription_list](#test-349)
- [Test 350: azmcp_subscription_list](#test-350)
- [Test 351: azmcp_azureterraformbestpractices_get](#test-351)
- [Test 352: azmcp_azureterraformbestpractices_get](#test-352)
- [Test 353: azmcp_virtualdesktop_hostpool_list](#test-353)
- [Test 354: azmcp_virtualdesktop_hostpool_sessionhost_list](#test-354)
- [Test 355: azmcp_virtualdesktop_hostpool_sessionhost_usersession-list](#test-355)
- [Test 356: azmcp_workbooks_create](#test-356)
- [Test 357: azmcp_workbooks_delete](#test-357)
- [Test 358: azmcp_workbooks_list](#test-358)
- [Test 359: azmcp_workbooks_list](#test-359)
- [Test 360: azmcp_workbooks_show](#test-360)
- [Test 361: azmcp_workbooks_show](#test-361)
- [Test 362: azmcp_workbooks_update](#test-362)
- [Test 363: azmcp_bicepschema_get](#test-363)
- [Test 364: azmcp_cloudarchitect_design](#test-364)
- [Test 365: azmcp_cloudarchitect_design](#test-365)
- [Test 366: azmcp_cloudarchitect_design](#test-366)
- [Test 367: azmcp_cloudarchitect_design](#test-367)

---

## Test 1

**Expected Tool:** `azmcp_foundry_agents_connect`  
**Prompt:** Query an agent in my AI foundry project  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.623362 | `azmcp_foundry_agents_connect` | ✅ **EXPECTED** |
| 2 | 0.602763 | `azmcp_foundry_agents_query-and-evaluate` | ❌ |
| 3 | 0.494915 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.442850 | `azmcp_foundry_agents_evaluate` | ❌ |
| 5 | 0.380394 | `azmcp_search_index_query` | ❌ |

---

## Test 2

**Expected Tool:** `azmcp_foundry_agents_evaluate`  
**Prompt:** Evaluate the full query and response I got from my agent for task_adherence  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.544099 | `azmcp_foundry_agents_query-and-evaluate` | ❌ |
| 2 | 0.469428 | `azmcp_foundry_agents_evaluate` | ✅ **EXPECTED** |
| 3 | 0.445964 | `azmcp_foundry_agents_connect` | ❌ |
| 4 | 0.235412 | `azmcp_foundry_agents_list` | ❌ |
| 5 | 0.233739 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 3

**Expected Tool:** `azmcp_foundry_agents_query-and-evaluate`  
**Prompt:** Query and evaluate an agent in my AI Foundry project for task_adherence  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.580566 | `azmcp_foundry_agents_query-and-evaluate` | ✅ **EXPECTED** |
| 2 | 0.568662 | `azmcp_foundry_agents_connect` | ❌ |
| 3 | 0.518655 | `azmcp_foundry_agents_evaluate` | ❌ |
| 4 | 0.381887 | `azmcp_foundry_agents_list` | ❌ |
| 5 | 0.326026 | `azmcp_foundry_models_deploy` | ❌ |

---

## Test 4

**Expected Tool:** `azmcp_foundry_knowledge_index_list`  
**Prompt:** List all knowledge indexes in my AI Foundry project  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.695201 | `azmcp_foundry_knowledge_index_list` | ✅ **EXPECTED** |
| 2 | 0.532985 | `azmcp_foundry_agents_list` | ❌ |
| 3 | 0.526485 | `azmcp_foundry_knowledge_index_schema` | ❌ |
| 4 | 0.433096 | `azmcp_foundry_models_list` | ❌ |
| 5 | 0.422779 | `azmcp_search_index_get` | ❌ |

---

## Test 5

**Expected Tool:** `azmcp_foundry_knowledge_index_list`  
**Prompt:** Show me the knowledge indexes in my AI Foundry project  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.604423 | `azmcp_foundry_knowledge_index_list` | ✅ **EXPECTED** |
| 2 | 0.490070 | `azmcp_foundry_knowledge_index_schema` | ❌ |
| 3 | 0.474561 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.397598 | `azmcp_foundry_models_list` | ❌ |
| 5 | 0.375536 | `azmcp_search_index_get` | ❌ |

---

## Test 6

**Expected Tool:** `azmcp_foundry_knowledge_index_schema`  
**Prompt:** Show me the schema for knowledge index <index-name> in my AI Foundry project  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.672563 | `azmcp_foundry_knowledge_index_schema` | ✅ **EXPECTED** |
| 2 | 0.564927 | `azmcp_foundry_knowledge_index_list` | ❌ |
| 3 | 0.424650 | `azmcp_search_index_get` | ❌ |
| 4 | 0.401680 | `azmcp_kusto_table_schema` | ❌ |
| 5 | 0.397208 | `azmcp_foundry_agents_list` | ❌ |

---

## Test 7

**Expected Tool:** `azmcp_foundry_knowledge_index_schema`  
**Prompt:** Get the schema configuration for knowledge index <index-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.650243 | `azmcp_foundry_knowledge_index_schema` | ✅ **EXPECTED** |
| 2 | 0.432759 | `azmcp_postgres_table_schema_get` | ❌ |
| 3 | 0.417523 | `azmcp_kusto_table_schema` | ❌ |
| 4 | 0.415963 | `azmcp_foundry_knowledge_index_list` | ❌ |
| 5 | 0.398546 | `azmcp_mysql_table_schema_get` | ❌ |

---

## Test 8

**Expected Tool:** `azmcp_foundry_models_deploy`  
**Prompt:** Deploy a GPT4o instance on my resource <resource-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.562920 | `azmcp_foundry_models_deploy` | ✅ **EXPECTED** |
| 2 | 0.282464 | `azmcp_mysql_server_list` | ❌ |
| 3 | 0.280674 | `azmcp_foundry_openai_create-completion` | ❌ |
| 4 | 0.274011 | `azmcp_deploy_plan_get` | ❌ |
| 5 | 0.269256 | `azmcp_loadtesting_testresource_create` | ❌ |

---

## Test 9

**Expected Tool:** `azmcp_foundry_models_deployments_list`  
**Prompt:** List all AI Foundry model deployments  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.663532 | `azmcp_foundry_models_deployments_list` | ✅ **EXPECTED** |
| 2 | 0.549623 | `azmcp_foundry_models_list` | ❌ |
| 3 | 0.539695 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.536115 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.448711 | `azmcp_search_service_list` | ❌ |

---

## Test 10

**Expected Tool:** `azmcp_foundry_models_deployments_list`  
**Prompt:** Show me all AI Foundry model deployments  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.606645 | `azmcp_foundry_models_deployments_list` | ✅ **EXPECTED** |
| 2 | 0.521475 | `azmcp_foundry_models_deploy` | ❌ |
| 3 | 0.518219 | `azmcp_foundry_models_list` | ❌ |
| 4 | 0.486395 | `azmcp_foundry_agents_list` | ❌ |
| 5 | 0.421169 | `azmcp_foundry_openai_create-completion` | ❌ |

---

## Test 11

**Expected Tool:** `azmcp_foundry_models_list`  
**Prompt:** List all AI Foundry models  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.559957 | `azmcp_foundry_models_list` | ✅ **EXPECTED** |
| 2 | 0.506770 | `azmcp_foundry_models_deployments_list` | ❌ |
| 3 | 0.491952 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.415089 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.387861 | `azmcp_foundry_knowledge_index_list` | ❌ |

---

## Test 12

**Expected Tool:** `azmcp_foundry_models_list`  
**Prompt:** Show me the available AI Foundry models  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.574794 | `azmcp_foundry_models_list` | ✅ **EXPECTED** |
| 2 | 0.497284 | `azmcp_foundry_models_deployments_list` | ❌ |
| 3 | 0.475139 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.467671 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.417075 | `azmcp_foundry_openai_create-completion` | ❌ |

---

## Test 13

**Expected Tool:** `azmcp_foundry_openai_create-completion`  
**Prompt:** Create a completion with the prompt "What is Azure?"  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.553675 | `azmcp_foundry_openai_create-completion` | ✅ **EXPECTED** |
| 2 | 0.403431 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.394144 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.386531 | `azmcp_get_bestpractices_get` | ❌ |
| 5 | 0.371786 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 14

**Expected Tool:** `azmcp_search_index_get`  
**Prompt:** Show me the details of the index <index-name> in Cognitive Search service <service-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.681052 | `azmcp_search_index_get` | ✅ **EXPECTED** |
| 2 | 0.544460 | `azmcp_foundry_knowledge_index_schema` | ❌ |
| 3 | 0.490624 | `azmcp_search_service_list` | ❌ |
| 4 | 0.466005 | `azmcp_foundry_knowledge_index_list` | ❌ |
| 5 | 0.459609 | `azmcp_search_index_query` | ❌ |

---

## Test 15

**Expected Tool:** `azmcp_search_index_get`  
**Prompt:** List all indexes in the Cognitive Search service <service-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.640256 | `azmcp_search_index_get` | ✅ **EXPECTED** |
| 2 | 0.620140 | `azmcp_search_service_list` | ❌ |
| 3 | 0.561856 | `azmcp_foundry_knowledge_index_list` | ❌ |
| 4 | 0.480817 | `azmcp_search_index_query` | ❌ |
| 5 | 0.453047 | `azmcp_foundry_agents_list` | ❌ |

---

## Test 16

**Expected Tool:** `azmcp_search_index_get`  
**Prompt:** Show me the indexes in the Cognitive Search service <service-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.620759 | `azmcp_search_index_get` | ✅ **EXPECTED** |
| 2 | 0.562775 | `azmcp_search_service_list` | ❌ |
| 3 | 0.561154 | `azmcp_foundry_knowledge_index_list` | ❌ |
| 4 | 0.471416 | `azmcp_search_index_query` | ❌ |
| 5 | 0.463814 | `azmcp_foundry_knowledge_index_schema` | ❌ |

---

## Test 17

**Expected Tool:** `azmcp_search_index_query`  
**Prompt:** Search for instances of <search_term> in the index <index-name> in Cognitive Search service <service-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.522826 | `azmcp_search_index_get` | ❌ |
| 2 | 0.515870 | `azmcp_search_index_query` | ✅ **EXPECTED** |
| 3 | 0.497467 | `azmcp_search_service_list` | ❌ |
| 4 | 0.437677 | `azmcp_postgres_database_query` | ❌ |
| 5 | 0.373917 | `azmcp_foundry_knowledge_index_list` | ❌ |

---

## Test 18

**Expected Tool:** `azmcp_search_service_list`  
**Prompt:** List all Cognitive Search services in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.793651 | `azmcp_search_service_list` | ✅ **EXPECTED** |
| 2 | 0.553011 | `azmcp_kusto_cluster_list` | ❌ |
| 3 | 0.520340 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.509461 | `azmcp_subscription_list` | ❌ |
| 5 | 0.505971 | `azmcp_search_index_get` | ❌ |

---

## Test 19

**Expected Tool:** `azmcp_search_service_list`  
**Prompt:** Show me the Cognitive Search services in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.686140 | `azmcp_search_service_list` | ✅ **EXPECTED** |
| 2 | 0.479898 | `azmcp_search_index_get` | ❌ |
| 3 | 0.467337 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.461786 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.453489 | `azmcp_marketplace_product_list` | ❌ |

---

## Test 20

**Expected Tool:** `azmcp_search_service_list`  
**Prompt:** Show me my Cognitive Search services  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.553025 | `azmcp_search_service_list` | ✅ **EXPECTED** |
| 2 | 0.436230 | `azmcp_search_index_get` | ❌ |
| 3 | 0.417096 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.404758 | `azmcp_search_index_query` | ❌ |
| 5 | 0.336174 | `azmcp_deploy_architecture_diagram_generate` | ❌ |

---

## Test 21

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Convert this audio file to text using Azure Speech Services  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.665995 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.351151 | `azmcp_deploy_plan_get` | ❌ |
| 3 | 0.342817 | `azmcp_foundry_openai_create-completion` | ❌ |
| 4 | 0.337734 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.335267 | `azmcp_search_index_query` | ❌ |

---

## Test 22

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Recognize speech from my audio file with language detection  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.511324 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.184542 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.159108 | `azmcp_foundry_agents_connect` | ❌ |
| 4 | 0.154918 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.145278 | `azmcp_applens_resource_diagnose` | ❌ |

---

## Test 23

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Transcribe speech from audio file <file_path> with profanity filtering  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.486489 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.180941 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.160209 | `azmcp_foundry_agents_connect` | ❌ |
| 4 | 0.156850 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.143871 | `azmcp_foundry_models_deploy` | ❌ |

---

## Test 24

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Convert speech to text from audio file <file_path> using endpoint <endpoint>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.611992 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.263196 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.237761 | `azmcp_foundry_agents_connect` | ❌ |
| 4 | 0.212149 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.203867 | `azmcp_foundry_models_deployments_list` | ❌ |

---

## Test 25

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Transcribe the audio file <file_path> in Spanish language  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.410533 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.152137 | `azmcp_foundry_models_deploy` | ❌ |
| 3 | 0.151632 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.142021 | `azmcp_foundry_openai_create-completion` | ❌ |
| 5 | 0.140373 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 26

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Convert speech to text with detailed output format from audio file <file_path>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.546259 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.210194 | `azmcp_loadtesting_testrun_get` | ❌ |
| 3 | 0.196743 | `azmcp_foundry_openai_create-completion` | ❌ |
| 4 | 0.183420 | `azmcp_extension_azqr` | ❌ |
| 5 | 0.181020 | `azmcp_search_index_get` | ❌ |

---

## Test 27

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Recognize speech from <file_path> with phrase hints for better accuracy  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.539963 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.246979 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.203413 | `azmcp_foundry_agents_connect` | ❌ |
| 4 | 0.179810 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.174984 | `azmcp_azureterraformbestpractices_get` | ❌ |

---

## Test 28

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Transcribe audio using multiple phrase hints: "Azure", "cognitive services", "machine learning"  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.549151 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.345661 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.337387 | `azmcp_cloudarchitect_design` | ❌ |
| 4 | 0.333076 | `azmcp_get_bestpractices_get` | ❌ |
| 5 | 0.324507 | `azmcp_deploy_pipeline_guidance_get` | ❌ |

---

## Test 29

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Convert speech to text with comma-separated phrase hints: "Azure, cognitive services, API"  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.532536 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.378382 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.326712 | `azmcp_get_bestpractices_get` | ❌ |
| 4 | 0.304769 | `azmcp_search_service_list` | ❌ |
| 5 | 0.301389 | `azmcp_foundry_agents_list` | ❌ |

---

## Test 30

**Expected Tool:** `azmcp_speech_stt_recognize`  
**Prompt:** Transcribe audio with raw profanity output from file <file_path>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.453396 | `azmcp_speech_stt_recognize` | ✅ **EXPECTED** |
| 2 | 0.181994 | `azmcp_foundry_openai_create-completion` | ❌ |
| 3 | 0.173205 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.160483 | `azmcp_foundry_agents_connect` | ❌ |
| 5 | 0.160185 | `azmcp_extension_azqr` | ❌ |

---

## Test 31

**Expected Tool:** `azmcp_appconfig_account_list`  
**Prompt:** List all App Configuration stores in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.786360 | `azmcp_appconfig_account_list` | ✅ **EXPECTED** |
| 2 | 0.530613 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.491380 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.481223 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.479988 | `azmcp_subscription_list` | ❌ |

---

## Test 32

**Expected Tool:** `azmcp_appconfig_account_list`  
**Prompt:** Show me the App Configuration stores in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.634978 | `azmcp_appconfig_account_list` | ✅ **EXPECTED** |
| 2 | 0.464865 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.398495 | `azmcp_subscription_list` | ❌ |
| 4 | 0.394373 | `azmcp_redis_list` | ❌ |
| 5 | 0.372456 | `azmcp_postgres_server_list` | ❌ |

---

## Test 33

**Expected Tool:** `azmcp_appconfig_account_list`  
**Prompt:** Show me my App Configuration stores  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.565435 | `azmcp_appconfig_account_list` | ✅ **EXPECTED** |
| 2 | 0.465344 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.355916 | `azmcp_postgres_server_config_get` | ❌ |
| 4 | 0.348661 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.327234 | `azmcp_appconfig_kv_set` | ❌ |

---

## Test 34

**Expected Tool:** `azmcp_appconfig_kv_delete`  
**Prompt:** Delete the key <key_name> in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.618277 | `azmcp_appconfig_kv_delete` | ✅ **EXPECTED** |
| 2 | 0.464358 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.424344 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.422700 | `azmcp_appconfig_kv_lock_set` | ❌ |
| 5 | 0.392016 | `azmcp_appconfig_account_list` | ❌ |

---

## Test 35

**Expected Tool:** `azmcp_appconfig_kv_get`  
**Prompt:** List all key-value settings in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.632687 | `azmcp_appconfig_kv_get` | ✅ **EXPECTED** |
| 2 | 0.557810 | `azmcp_appconfig_account_list` | ❌ |
| 3 | 0.530884 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.464635 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.439089 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 36

**Expected Tool:** `azmcp_appconfig_kv_get`  
**Prompt:** Show me the key-value settings in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.612555 | `azmcp_appconfig_kv_get` | ✅ **EXPECTED** |
| 2 | 0.522426 | `azmcp_appconfig_account_list` | ❌ |
| 3 | 0.512945 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.468503 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.457866 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 37

**Expected Tool:** `azmcp_appconfig_kv_get`  
**Prompt:** List all key-value settings with key name starting with 'prod-' in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.512883 | `azmcp_appconfig_kv_get` | ✅ **EXPECTED** |
| 2 | 0.449905 | `azmcp_appconfig_account_list` | ❌ |
| 3 | 0.398684 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.380614 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.346166 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 38

**Expected Tool:** `azmcp_appconfig_kv_get`  
**Prompt:** Show the content for the key <key_name> in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.552300 | `azmcp_appconfig_kv_get` | ✅ **EXPECTED** |
| 2 | 0.448912 | `azmcp_appconfig_kv_set` | ❌ |
| 3 | 0.441713 | `azmcp_appconfig_kv_delete` | ❌ |
| 4 | 0.437432 | `azmcp_appconfig_account_list` | ❌ |
| 5 | 0.416264 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 39

**Expected Tool:** `azmcp_appconfig_kv_lock_set`  
**Prompt:** Lock the key <key_name> in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.591237 | `azmcp_appconfig_kv_lock_set` | ✅ **EXPECTED** |
| 2 | 0.487174 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.445551 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.431516 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.373656 | `azmcp_appconfig_account_list` | ❌ |

---

## Test 40

**Expected Tool:** `azmcp_appconfig_kv_lock_set`  
**Prompt:** Unlock the key <key_name> in App Configuration store <app_config_store_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.555699 | `azmcp_appconfig_kv_lock_set` | ✅ **EXPECTED** |
| 2 | 0.505681 | `azmcp_appconfig_kv_get` | ❌ |
| 3 | 0.476496 | `azmcp_appconfig_kv_delete` | ❌ |
| 4 | 0.425488 | `azmcp_appconfig_kv_set` | ❌ |
| 5 | 0.409406 | `azmcp_appconfig_account_list` | ❌ |

---

## Test 41

**Expected Tool:** `azmcp_appconfig_kv_set`  
**Prompt:** Set the key <key_name> in App Configuration store <app_config_store_name> to <value>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609635 | `azmcp_appconfig_kv_set` | ✅ **EXPECTED** |
| 2 | 0.536497 | `azmcp_appconfig_kv_lock_set` | ❌ |
| 3 | 0.512707 | `azmcp_appconfig_kv_get` | ❌ |
| 4 | 0.505571 | `azmcp_appconfig_kv_delete` | ❌ |
| 5 | 0.377919 | `azmcp_appconfig_account_list` | ❌ |

---

## Test 42

**Expected Tool:** `azmcp_applens_resource_diagnose`  
**Prompt:** Please help me diagnose issues with my app using app lens  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.595594 | `azmcp_applens_resource_diagnose` | ✅ **EXPECTED** |
| 2 | 0.336090 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.300786 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 4 | 0.273082 | `azmcp_cloudarchitect_design` | ❌ |
| 5 | 0.216077 | `azmcp_get_bestpractices_get` | ❌ |

---

## Test 43

**Expected Tool:** `azmcp_applens_resource_diagnose`  
**Prompt:** Use app lens to check why my app is slow?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.502381 | `azmcp_applens_resource_diagnose` | ✅ **EXPECTED** |
| 2 | 0.316297 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.255570 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 4 | 0.225972 | `azmcp_quota_usage_check` | ❌ |
| 5 | 0.223847 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 44

**Expected Tool:** `azmcp_applens_resource_diagnose`  
**Prompt:** What does app lens say is wrong with my service?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.492830 | `azmcp_applens_resource_diagnose` | ✅ **EXPECTED** |
| 2 | 0.256325 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 3 | 0.242574 | `azmcp_cloudarchitect_design` | ❌ |
| 4 | 0.225608 | `azmcp_resourcehealth_service-health-events_list` | ❌ |
| 5 | 0.216177 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 45

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add a database connection to my app service <app_name> in resource group <resource_group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.729094 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.398617 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.380126 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.368237 | `azmcp_sql_db_list` | ❌ |
| 5 | 0.364437 | `azmcp_mysql_server_list` | ❌ |

---

## Test 46

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Configure a SQL Server database for app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.612088 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.473224 | `azmcp_sql_db_update` | ❌ |
| 3 | 0.471103 | `azmcp_sql_db_create` | ❌ |
| 4 | 0.454417 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.412229 | `azmcp_sql_server_delete` | ❌ |

---

## Test 47

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add a MySQL database to app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.648444 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.418902 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.409593 | `azmcp_mysql_database_list` | ❌ |
| 4 | 0.397907 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.382602 | `azmcp_mysql_server_list` | ❌ |

---

## Test 48

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add a PostgreSQL database to app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.579461 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.449085 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.416337 | `azmcp_postgres_server_param_set` | ❌ |
| 4 | 0.409515 | `azmcp_postgres_table_list` | ❌ |
| 5 | 0.405431 | `azmcp_postgres_server_list` | ❌ |

---

## Test 49

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add a CosmosDB database to app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.643008 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.477031 | `azmcp_cosmos_database_list` | ❌ |
| 3 | 0.465637 | `azmcp_sql_db_create` | ❌ |
| 4 | 0.431581 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.428178 | `azmcp_cosmos_database_container_item_query` | ❌ |

---

## Test 50

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add database <database_name> on server <database_server> to app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.645486 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.489228 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.440007 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.431453 | `azmcp_sql_db_delete` | ❌ |
| 5 | 0.426090 | `azmcp_sql_server_delete` | ❌ |

---

## Test 51

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Set connection string for database <database_name> in app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.665201 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.401714 | `azmcp_sql_db_rename` | ❌ |
| 3 | 0.369071 | `azmcp_sql_db_create` | ❌ |
| 4 | 0.332119 | `azmcp_appconfig_kv_set` | ❌ |
| 5 | 0.328637 | `azmcp_sql_db_update` | ❌ |

---

## Test 52

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Configure tenant <tenant> for database <database_name> in app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.536723 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.408796 | `azmcp_sql_db_rename` | ❌ |
| 3 | 0.394572 | `azmcp_sql_db_create` | ❌ |
| 4 | 0.355309 | `azmcp_sql_db_update` | ❌ |
| 5 | 0.329110 | `azmcp_keyvault_secret_create` | ❌ |

---

## Test 53

**Expected Tool:** `azmcp_appservice_database_add`  
**Prompt:** Add database <database_name> with retry policy to app service <app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.560240 | `azmcp_appservice_database_add` | ✅ **EXPECTED** |
| 2 | 0.426753 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.392376 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.371892 | `azmcp_sql_db_delete` | ❌ |
| 5 | 0.361028 | `azmcp_cosmos_database_list` | ❌ |

---

## Test 54

**Expected Tool:** `azmcp_applicationinsights_recommendation_list`  
**Prompt:** List code optimization recommendations across my Application Insights components  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.572473 | `azmcp_applicationinsights_recommendation_list` | ✅ **EXPECTED** |
| 2 | 0.445157 | `azmcp_get_bestpractices_get` | ❌ |
| 3 | 0.390478 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 4 | 0.383903 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.375286 | `azmcp_deploy_iac_rules_get` | ❌ |

---

## Test 55

**Expected Tool:** `azmcp_applicationinsights_recommendation_list`  
**Prompt:** Show me code optimization recommendations for all Application Insights resources in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.696531 | `azmcp_applicationinsights_recommendation_list` | ✅ **EXPECTED** |
| 2 | 0.468384 | `azmcp_get_bestpractices_get` | ❌ |
| 3 | 0.452230 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.435241 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 5 | 0.424622 | `azmcp_search_service_list` | ❌ |

---

## Test 56

**Expected Tool:** `azmcp_applicationinsights_recommendation_list`  
**Prompt:** List profiler recommendations for Application Insights in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.626722 | `azmcp_applicationinsights_recommendation_list` | ✅ **EXPECTED** |
| 2 | 0.479392 | `azmcp_mysql_server_list` | ❌ |
| 3 | 0.477409 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.468861 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.467569 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 57

**Expected Tool:** `azmcp_applicationinsights_recommendation_list`  
**Prompt:** Show me performance improvement recommendations from Application Insights  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.509502 | `azmcp_applicationinsights_recommendation_list` | ✅ **EXPECTED** |
| 2 | 0.419690 | `azmcp_applens_resource_diagnose` | ❌ |
| 3 | 0.383767 | `azmcp_get_bestpractices_get` | ❌ |
| 4 | 0.367278 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 5 | 0.343931 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 58

**Expected Tool:** `azmcp_acr_registry_list`  
**Prompt:** List all Azure Container Registries in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.743538 | `azmcp_acr_registry_list` | ✅ **EXPECTED** |
| 2 | 0.711580 | `azmcp_acr_registry_repository_list` | ❌ |
| 3 | 0.585675 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.541506 | `azmcp_search_service_list` | ❌ |
| 5 | 0.527457 | `azmcp_aks_cluster_list` | ❌ |

---

## Test 59

**Expected Tool:** `azmcp_acr_registry_list`  
**Prompt:** Show me my Azure Container Registries  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.585940 | `azmcp_acr_registry_list` | ✅ **EXPECTED** |
| 2 | 0.563636 | `azmcp_acr_registry_repository_list` | ❌ |
| 3 | 0.450287 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.420282 | `azmcp_redis_list` | ❌ |
| 5 | 0.415552 | `azmcp_cosmos_database_container_list` | ❌ |

---

## Test 60

**Expected Tool:** `azmcp_acr_registry_list`  
**Prompt:** Show me the container registries in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.637164 | `azmcp_acr_registry_list` | ✅ **EXPECTED** |
| 2 | 0.563476 | `azmcp_acr_registry_repository_list` | ❌ |
| 3 | 0.516769 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.483510 | `azmcp_redis_list` | ❌ |
| 5 | 0.466160 | `azmcp_subscription_list` | ❌ |

---

## Test 61

**Expected Tool:** `azmcp_acr_registry_list`  
**Prompt:** List container registries in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.654318 | `azmcp_acr_registry_repository_list` | ❌ |
| 2 | 0.633856 | `azmcp_acr_registry_list` | ✅ **EXPECTED** |
| 3 | 0.476015 | `azmcp_mysql_server_list` | ❌ |
| 4 | 0.454929 | `azmcp_group_list` | ❌ |
| 5 | 0.453903 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 62

**Expected Tool:** `azmcp_acr_registry_list`  
**Prompt:** Show me the container registries in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.639315 | `azmcp_acr_registry_list` | ✅ **EXPECTED** |
| 2 | 0.637972 | `azmcp_acr_registry_repository_list` | ❌ |
| 3 | 0.468028 | `azmcp_mysql_server_list` | ❌ |
| 4 | 0.449530 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 5 | 0.445741 | `azmcp_group_list` | ❌ |

---

## Test 63

**Expected Tool:** `azmcp_acr_registry_repository_list`  
**Prompt:** List all container registry repositories in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.626482 | `azmcp_acr_registry_repository_list` | ✅ **EXPECTED** |
| 2 | 0.617547 | `azmcp_acr_registry_list` | ❌ |
| 3 | 0.544172 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.495567 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.486088 | `azmcp_redis_list` | ❌ |

---

## Test 64

**Expected Tool:** `azmcp_acr_registry_repository_list`  
**Prompt:** Show me my container registry repositories  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.546333 | `azmcp_acr_registry_repository_list` | ✅ **EXPECTED** |
| 2 | 0.469285 | `azmcp_acr_registry_list` | ❌ |
| 3 | 0.407973 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.400145 | `azmcp_storage_blob_container_get` | ❌ |
| 5 | 0.361932 | `azmcp_redis_list` | ❌ |

---

## Test 65

**Expected Tool:** `azmcp_acr_registry_repository_list`  
**Prompt:** List repositories in the container registry <registry_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.674296 | `azmcp_acr_registry_repository_list` | ✅ **EXPECTED** |
| 2 | 0.541713 | `azmcp_acr_registry_list` | ❌ |
| 3 | 0.433927 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.388490 | `azmcp_storage_blob_container_get` | ❌ |
| 5 | 0.383109 | `azmcp_kusto_database_list` | ❌ |

---

## Test 66

**Expected Tool:** `azmcp_acr_registry_repository_list`  
**Prompt:** Show me the repositories in the container registry <registry_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.600780 | `azmcp_acr_registry_repository_list` | ✅ **EXPECTED** |
| 2 | 0.501800 | `azmcp_acr_registry_list` | ❌ |
| 3 | 0.418623 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.375939 | `azmcp_redis_list` | ❌ |
| 5 | 0.374628 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 67

**Expected Tool:** `azmcp_cosmos_account_list`  
**Prompt:** List all cosmosdb accounts in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.818337 | `azmcp_cosmos_account_list` | ✅ **EXPECTED** |
| 2 | 0.668480 | `azmcp_cosmos_database_list` | ❌ |
| 3 | 0.636036 | `azmcp_subscription_list` | ❌ |
| 4 | 0.615268 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.601467 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 68

**Expected Tool:** `azmcp_cosmos_account_list`  
**Prompt:** Show me my cosmosdb accounts  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.665370 | `azmcp_cosmos_account_list` | ✅ **EXPECTED** |
| 2 | 0.605357 | `azmcp_cosmos_database_list` | ❌ |
| 3 | 0.571613 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.549447 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.494741 | `azmcp_subscription_list` | ❌ |

---

## Test 69

**Expected Tool:** `azmcp_cosmos_account_list`  
**Prompt:** Show me the cosmosdb accounts in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.752487 | `azmcp_cosmos_account_list` | ✅ **EXPECTED** |
| 2 | 0.607201 | `azmcp_subscription_list` | ❌ |
| 3 | 0.605125 | `azmcp_cosmos_database_list` | ❌ |
| 4 | 0.566249 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.563921 | `azmcp_cosmos_database_container_item_query` | ❌ |

---

## Test 70

**Expected Tool:** `azmcp_cosmos_database_container_item_query`  
**Prompt:** Show me the items that contain the word <search_term> in the container <container_name> in the database <database_name> for the cosmosdb account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.658701 | `azmcp_cosmos_database_container_item_query` | ✅ **EXPECTED** |
| 2 | 0.605253 | `azmcp_cosmos_database_container_list` | ❌ |
| 3 | 0.477874 | `azmcp_cosmos_database_list` | ❌ |
| 4 | 0.447734 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.445640 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 71

**Expected Tool:** `azmcp_cosmos_database_container_list`  
**Prompt:** List all the containers in the database <database_name> for the cosmosdb account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.852832 | `azmcp_cosmos_database_container_list` | ✅ **EXPECTED** |
| 2 | 0.681044 | `azmcp_cosmos_database_list` | ❌ |
| 3 | 0.680762 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 4 | 0.630576 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.581593 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 72

**Expected Tool:** `azmcp_cosmos_database_container_list`  
**Prompt:** Show me the containers in the database <database_name> for the cosmosdb account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.789395 | `azmcp_cosmos_database_container_list` | ✅ **EXPECTED** |
| 2 | 0.648126 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 3 | 0.614220 | `azmcp_cosmos_database_list` | ❌ |
| 4 | 0.561986 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.537286 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 73

**Expected Tool:** `azmcp_cosmos_database_list`  
**Prompt:** List all the databases in the cosmosdb account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.815683 | `azmcp_cosmos_database_list` | ✅ **EXPECTED** |
| 2 | 0.668455 | `azmcp_cosmos_account_list` | ❌ |
| 3 | 0.665298 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.606433 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.583490 | `azmcp_kusto_database_list` | ❌ |

---

## Test 74

**Expected Tool:** `azmcp_cosmos_database_list`  
**Prompt:** Show me the databases in the cosmosdb account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.749370 | `azmcp_cosmos_database_list` | ✅ **EXPECTED** |
| 2 | 0.624759 | `azmcp_cosmos_database_container_list` | ❌ |
| 3 | 0.614516 | `azmcp_cosmos_account_list` | ❌ |
| 4 | 0.579919 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.538479 | `azmcp_mysql_database_list` | ❌ |

---

## Test 75

**Expected Tool:** `azmcp_kusto_cluster_get`  
**Prompt:** Show me the details of the Data Explorer cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.592626 | `azmcp_kusto_cluster_get` | ✅ **EXPECTED** |
| 2 | 0.464573 | `azmcp_aks_cluster_get` | ❌ |
| 3 | 0.463832 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.428159 | `azmcp_kusto_query` | ❌ |
| 5 | 0.425724 | `azmcp_kusto_database_list` | ❌ |

---

## Test 76

**Expected Tool:** `azmcp_kusto_cluster_list`  
**Prompt:** List all Data Explorer clusters in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.793748 | `azmcp_kusto_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.630500 | `azmcp_kusto_database_list` | ❌ |
| 3 | 0.571747 | `azmcp_kusto_cluster_get` | ❌ |
| 4 | 0.535979 | `azmcp_aks_cluster_list` | ❌ |
| 5 | 0.509396 | `azmcp_grafana_list` | ❌ |

---

## Test 77

**Expected Tool:** `azmcp_kusto_cluster_list`  
**Prompt:** Show me my Data Explorer clusters  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.531307 | `azmcp_kusto_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.467792 | `azmcp_kusto_cluster_get` | ❌ |
| 3 | 0.432365 | `azmcp_kusto_database_list` | ❌ |
| 4 | 0.391110 | `azmcp_redis_cluster_database_list` | ❌ |
| 5 | 0.367024 | `azmcp_redis_list` | ❌ |

---

## Test 78

**Expected Tool:** `azmcp_kusto_cluster_list`  
**Prompt:** Show me the Data Explorer clusters in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.701484 | `azmcp_kusto_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.572336 | `azmcp_kusto_cluster_get` | ❌ |
| 3 | 0.548748 | `azmcp_kusto_database_list` | ❌ |
| 4 | 0.479685 | `azmcp_redis_list` | ❌ |
| 5 | 0.471120 | `azmcp_aks_cluster_list` | ❌ |

---

## Test 79

**Expected Tool:** `azmcp_kusto_database_list`  
**Prompt:** List all databases in the Data Explorer cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.677092 | `azmcp_kusto_database_list` | ✅ **EXPECTED** |
| 2 | 0.628161 | `azmcp_redis_cluster_database_list` | ❌ |
| 3 | 0.560592 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.556795 | `azmcp_kusto_table_list` | ❌ |
| 5 | 0.553218 | `azmcp_postgres_database_list` | ❌ |

---

## Test 80

**Expected Tool:** `azmcp_kusto_database_list`  
**Prompt:** Show me the databases in the Data Explorer cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.623590 | `azmcp_kusto_database_list` | ✅ **EXPECTED** |
| 2 | 0.598016 | `azmcp_redis_cluster_database_list` | ❌ |
| 3 | 0.509953 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.507073 | `azmcp_kusto_table_list` | ❌ |
| 5 | 0.497144 | `azmcp_cosmos_database_list` | ❌ |

---

## Test 81

**Expected Tool:** `azmcp_kusto_query`  
**Prompt:** Show me all items that contain the word <search_term> in the Data Explorer table <table_name> in cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.423660 | `azmcp_kusto_query` | ✅ **EXPECTED** |
| 2 | 0.409475 | `azmcp_postgres_database_query` | ❌ |
| 3 | 0.407741 | `azmcp_kusto_sample` | ❌ |
| 4 | 0.407656 | `azmcp_kusto_table_schema` | ❌ |
| 5 | 0.403990 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 82

**Expected Tool:** `azmcp_kusto_sample`  
**Prompt:** Show me a data sample from the Data Explorer table <table_name> in cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.595554 | `azmcp_kusto_sample` | ✅ **EXPECTED** |
| 2 | 0.509594 | `azmcp_kusto_table_schema` | ❌ |
| 3 | 0.424212 | `azmcp_kusto_table_list` | ❌ |
| 4 | 0.401703 | `azmcp_kusto_cluster_get` | ❌ |
| 5 | 0.400924 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 83

**Expected Tool:** `azmcp_kusto_table_list`  
**Prompt:** List all tables in the Data Explorer database <database_name> in cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.679374 | `azmcp_kusto_table_list` | ✅ **EXPECTED** |
| 2 | 0.585055 | `azmcp_postgres_table_list` | ❌ |
| 3 | 0.581086 | `azmcp_kusto_database_list` | ❌ |
| 4 | 0.556434 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.549861 | `azmcp_monitor_table_list` | ❌ |

---

## Test 84

**Expected Tool:** `azmcp_kusto_table_list`  
**Prompt:** Show me the tables in the Data Explorer database <database_name> in cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.619332 | `azmcp_kusto_table_list` | ✅ **EXPECTED** |
| 2 | 0.553834 | `azmcp_kusto_table_schema` | ❌ |
| 3 | 0.527676 | `azmcp_kusto_database_list` | ❌ |
| 4 | 0.524835 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.523502 | `azmcp_postgres_table_list` | ❌ |

---

## Test 85

**Expected Tool:** `azmcp_kusto_table_schema`  
**Prompt:** Show me the schema for table <table_name> in the Data Explorer database <database_name> in cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.667074 | `azmcp_kusto_table_schema` | ✅ **EXPECTED** |
| 2 | 0.564327 | `azmcp_postgres_table_schema_get` | ❌ |
| 3 | 0.528045 | `azmcp_mysql_table_schema_get` | ❌ |
| 4 | 0.490979 | `azmcp_kusto_sample` | ❌ |
| 5 | 0.490072 | `azmcp_kusto_table_list` | ❌ |

---

## Test 86

**Expected Tool:** `azmcp_mysql_database_list`  
**Prompt:** List all MySQL databases in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.634056 | `azmcp_postgres_database_list` | ❌ |
| 2 | 0.623421 | `azmcp_mysql_database_list` | ✅ **EXPECTED** |
| 3 | 0.534457 | `azmcp_mysql_table_list` | ❌ |
| 4 | 0.498918 | `azmcp_mysql_server_list` | ❌ |
| 5 | 0.490175 | `azmcp_sql_db_list` | ❌ |

---

## Test 87

**Expected Tool:** `azmcp_mysql_database_list`  
**Prompt:** Show me the MySQL databases in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.588122 | `azmcp_mysql_database_list` | ✅ **EXPECTED** |
| 2 | 0.574089 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.483855 | `azmcp_mysql_table_list` | ❌ |
| 4 | 0.463244 | `azmcp_mysql_server_list` | ❌ |
| 5 | 0.448191 | `azmcp_redis_cluster_database_list` | ❌ |

---

## Test 88

**Expected Tool:** `azmcp_mysql_database_query`  
**Prompt:** Show me all items that contain the word <search_term> in the MySQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.476423 | `azmcp_mysql_table_list` | ❌ |
| 2 | 0.455770 | `azmcp_mysql_database_list` | ❌ |
| 3 | 0.433392 | `azmcp_mysql_database_query` | ✅ **EXPECTED** |
| 4 | 0.419859 | `azmcp_mysql_server_list` | ❌ |
| 5 | 0.409321 | `azmcp_mysql_table_schema_get` | ❌ |

---

## Test 89

**Expected Tool:** `azmcp_mysql_server_config_get`  
**Prompt:** Show me the configuration of MySQL server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.531887 | `azmcp_postgres_server_config_get` | ❌ |
| 2 | 0.516894 | `azmcp_mysql_server_param_set` | ❌ |
| 3 | 0.489816 | `azmcp_mysql_server_config_get` | ✅ **EXPECTED** |
| 4 | 0.476863 | `azmcp_mysql_server_param_get` | ❌ |
| 5 | 0.426444 | `azmcp_mysql_table_schema_get` | ❌ |

---

## Test 90

**Expected Tool:** `azmcp_mysql_server_list`  
**Prompt:** List all MySQL servers in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.678472 | `azmcp_postgres_server_list` | ❌ |
| 2 | 0.558177 | `azmcp_mysql_database_list` | ❌ |
| 3 | 0.554817 | `azmcp_mysql_server_list` | ✅ **EXPECTED** |
| 4 | 0.513706 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.501199 | `azmcp_mysql_table_list` | ❌ |

---

## Test 91

**Expected Tool:** `azmcp_mysql_server_list`  
**Prompt:** Show me my MySQL servers  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.478518 | `azmcp_mysql_database_list` | ❌ |
| 2 | 0.474586 | `azmcp_mysql_server_list` | ✅ **EXPECTED** |
| 3 | 0.435642 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.412380 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.389993 | `azmcp_postgres_database_list` | ❌ |

---

## Test 92

**Expected Tool:** `azmcp_mysql_server_list`  
**Prompt:** Show me the MySQL servers in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.636435 | `azmcp_postgres_server_list` | ❌ |
| 2 | 0.534266 | `azmcp_mysql_server_list` | ✅ **EXPECTED** |
| 3 | 0.530210 | `azmcp_mysql_database_list` | ❌ |
| 4 | 0.475052 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.466729 | `azmcp_redis_list` | ❌ |

---

## Test 93

**Expected Tool:** `azmcp_mysql_server_param_get`  
**Prompt:** Show me the value of connection timeout in seconds in my MySQL server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.495071 | `azmcp_mysql_server_param_get` | ✅ **EXPECTED** |
| 2 | 0.438075 | `azmcp_mysql_server_param_set` | ❌ |
| 3 | 0.333841 | `azmcp_mysql_database_query` | ❌ |
| 4 | 0.313558 | `azmcp_mysql_table_schema_get` | ❌ |
| 5 | 0.310782 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 94

**Expected Tool:** `azmcp_mysql_server_param_set`  
**Prompt:** Set connection timeout to 20 seconds for my MySQL server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.449419 | `azmcp_mysql_server_param_set` | ✅ **EXPECTED** |
| 2 | 0.381144 | `azmcp_mysql_server_param_get` | ❌ |
| 3 | 0.303499 | `azmcp_postgres_server_param_set` | ❌ |
| 4 | 0.298911 | `azmcp_mysql_database_query` | ❌ |
| 5 | 0.277627 | `azmcp_appservice_database_add` | ❌ |

---

## Test 95

**Expected Tool:** `azmcp_mysql_table_list`  
**Prompt:** List all tables in the MySQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.633448 | `azmcp_mysql_table_list` | ✅ **EXPECTED** |
| 2 | 0.573844 | `azmcp_postgres_table_list` | ❌ |
| 3 | 0.550898 | `azmcp_postgres_database_list` | ❌ |
| 4 | 0.546963 | `azmcp_mysql_database_list` | ❌ |
| 5 | 0.511847 | `azmcp_kusto_table_list` | ❌ |

---

## Test 96

**Expected Tool:** `azmcp_mysql_table_list`  
**Prompt:** Show me the tables in the MySQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609131 | `azmcp_mysql_table_list` | ✅ **EXPECTED** |
| 2 | 0.526236 | `azmcp_postgres_table_list` | ❌ |
| 3 | 0.525709 | `azmcp_mysql_database_list` | ❌ |
| 4 | 0.506867 | `azmcp_mysql_table_schema_get` | ❌ |
| 5 | 0.498050 | `azmcp_postgres_database_list` | ❌ |

---

## Test 97

**Expected Tool:** `azmcp_mysql_table_schema_get`  
**Prompt:** Show me the schema of table <table> in the MySQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.630708 | `azmcp_mysql_table_schema_get` | ✅ **EXPECTED** |
| 2 | 0.558306 | `azmcp_postgres_table_schema_get` | ❌ |
| 3 | 0.545025 | `azmcp_mysql_table_list` | ❌ |
| 4 | 0.517935 | `azmcp_kusto_table_schema` | ❌ |
| 5 | 0.457739 | `azmcp_mysql_database_list` | ❌ |

---

## Test 98

**Expected Tool:** `azmcp_postgres_database_list`  
**Prompt:** List all PostgreSQL databases in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.815617 | `azmcp_postgres_database_list` | ✅ **EXPECTED** |
| 2 | 0.644014 | `azmcp_postgres_table_list` | ❌ |
| 3 | 0.622790 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.542685 | `azmcp_postgres_server_config_get` | ❌ |
| 5 | 0.490955 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 99

**Expected Tool:** `azmcp_postgres_database_list`  
**Prompt:** Show me the PostgreSQL databases in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.760033 | `azmcp_postgres_database_list` | ✅ **EXPECTED** |
| 2 | 0.589783 | `azmcp_postgres_server_list` | ❌ |
| 3 | 0.585891 | `azmcp_postgres_table_list` | ❌ |
| 4 | 0.552660 | `azmcp_postgres_server_config_get` | ❌ |
| 5 | 0.495683 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 100

**Expected Tool:** `azmcp_postgres_database_query`  
**Prompt:** Show me all items that contain the word <search_term> in the PostgreSQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.546200 | `azmcp_postgres_database_list` | ❌ |
| 2 | 0.523087 | `azmcp_postgres_database_query` | ✅ **EXPECTED** |
| 3 | 0.503232 | `azmcp_postgres_table_list` | ❌ |
| 4 | 0.466610 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.403940 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 101

**Expected Tool:** `azmcp_postgres_server_config_get`  
**Prompt:** Show me the configuration of PostgreSQL server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.756593 | `azmcp_postgres_server_config_get` | ✅ **EXPECTED** |
| 2 | 0.615429 | `azmcp_postgres_server_param_set` | ❌ |
| 3 | 0.599518 | `azmcp_postgres_server_param_get` | ❌ |
| 4 | 0.535049 | `azmcp_postgres_database_list` | ❌ |
| 5 | 0.518574 | `azmcp_postgres_server_list` | ❌ |

---

## Test 102

**Expected Tool:** `azmcp_postgres_server_list`  
**Prompt:** List all PostgreSQL servers in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.900023 | `azmcp_postgres_server_list` | ✅ **EXPECTED** |
| 2 | 0.640733 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.565914 | `azmcp_postgres_table_list` | ❌ |
| 4 | 0.538997 | `azmcp_postgres_server_config_get` | ❌ |
| 5 | 0.534239 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 103

**Expected Tool:** `azmcp_postgres_server_list`  
**Prompt:** Show me my PostgreSQL servers  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.674327 | `azmcp_postgres_server_list` | ✅ **EXPECTED** |
| 2 | 0.607062 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.576349 | `azmcp_postgres_server_config_get` | ❌ |
| 4 | 0.522996 | `azmcp_postgres_table_list` | ❌ |
| 5 | 0.506262 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 104

**Expected Tool:** `azmcp_postgres_server_list`  
**Prompt:** Show me the PostgreSQL servers in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.832155 | `azmcp_postgres_server_list` | ✅ **EXPECTED** |
| 2 | 0.579232 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.531804 | `azmcp_postgres_server_config_get` | ❌ |
| 4 | 0.514445 | `azmcp_postgres_table_list` | ❌ |
| 5 | 0.505970 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 105

**Expected Tool:** `azmcp_postgres_server_param_get`  
**Prompt:** Show me if the parameter my PostgreSQL server <server> has replication enabled  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.594733 | `azmcp_postgres_server_param_get` | ✅ **EXPECTED** |
| 2 | 0.552678 | `azmcp_postgres_server_param_set` | ❌ |
| 3 | 0.539671 | `azmcp_postgres_server_config_get` | ❌ |
| 4 | 0.489693 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.451871 | `azmcp_postgres_database_list` | ❌ |

---

## Test 106

**Expected Tool:** `azmcp_postgres_server_param_set`  
**Prompt:** Enable replication for my PostgreSQL server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.579873 | `azmcp_postgres_server_param_set` | ✅ **EXPECTED** |
| 2 | 0.488474 | `azmcp_postgres_server_config_get` | ❌ |
| 3 | 0.469794 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.447026 | `azmcp_postgres_server_param_get` | ❌ |
| 5 | 0.440760 | `azmcp_postgres_database_list` | ❌ |

---

## Test 107

**Expected Tool:** `azmcp_postgres_table_list`  
**Prompt:** List all tables in the PostgreSQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.789883 | `azmcp_postgres_table_list` | ✅ **EXPECTED** |
| 2 | 0.750580 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.574930 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.519820 | `azmcp_postgres_table_schema_get` | ❌ |
| 5 | 0.501400 | `azmcp_postgres_server_config_get` | ❌ |

---

## Test 108

**Expected Tool:** `azmcp_postgres_table_list`  
**Prompt:** Show me the tables in the PostgreSQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.736083 | `azmcp_postgres_table_list` | ✅ **EXPECTED** |
| 2 | 0.690112 | `azmcp_postgres_database_list` | ❌ |
| 3 | 0.558357 | `azmcp_postgres_table_schema_get` | ❌ |
| 4 | 0.543331 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.521570 | `azmcp_postgres_server_config_get` | ❌ |

---

## Test 109

**Expected Tool:** `azmcp_postgres_table_schema_get`  
**Prompt:** Show me the schema of table <table> in the PostgreSQL database <database> in server <server>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.714877 | `azmcp_postgres_table_schema_get` | ✅ **EXPECTED** |
| 2 | 0.597846 | `azmcp_postgres_table_list` | ❌ |
| 3 | 0.574230 | `azmcp_postgres_database_list` | ❌ |
| 4 | 0.508082 | `azmcp_postgres_server_config_get` | ❌ |
| 5 | 0.503154 | `azmcp_kusto_table_schema` | ❌ |

---

## Test 110

**Expected Tool:** `azmcp_deploy_app_logs_get`  
**Prompt:** Show me the log of the application deployed by azd  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.711770 | `azmcp_deploy_app_logs_get` | ✅ **EXPECTED** |
| 2 | 0.471692 | `azmcp_deploy_plan_get` | ❌ |
| 3 | 0.404890 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.398467 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.392565 | `azmcp_deploy_iac_rules_get` | ❌ |

---

## Test 111

**Expected Tool:** `azmcp_deploy_architecture_diagram_generate`  
**Prompt:** Generate the azure architecture diagram for this application  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.680640 | `azmcp_deploy_architecture_diagram_generate` | ✅ **EXPECTED** |
| 2 | 0.562521 | `azmcp_deploy_plan_get` | ❌ |
| 3 | 0.497193 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.489344 | `azmcp_cloudarchitect_design` | ❌ |
| 5 | 0.435921 | `azmcp_deploy_iac_rules_get` | ❌ |

---

## Test 112

**Expected Tool:** `azmcp_deploy_iac_rules_get`  
**Prompt:** Show me the rules to generate bicep scripts  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.529092 | `azmcp_deploy_iac_rules_get` | ✅ **EXPECTED** |
| 2 | 0.404829 | `azmcp_bicepschema_get` | ❌ |
| 3 | 0.391965 | `azmcp_get_bestpractices_get` | ❌ |
| 4 | 0.383210 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 5 | 0.341436 | `azmcp_deploy_pipeline_guidance_get` | ❌ |

---

## Test 113

**Expected Tool:** `azmcp_deploy_pipeline_guidance_get`  
**Prompt:** How can I create a CI/CD pipeline to deploy this app to Azure?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.638841 | `azmcp_deploy_pipeline_guidance_get` | ✅ **EXPECTED** |
| 2 | 0.499242 | `azmcp_deploy_plan_get` | ❌ |
| 3 | 0.448918 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.385920 | `azmcp_deploy_app_logs_get` | ❌ |
| 5 | 0.382240 | `azmcp_get_bestpractices_get` | ❌ |

---

## Test 114

**Expected Tool:** `azmcp_deploy_plan_get`  
**Prompt:** Create a plan to deploy this application to azure  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.688055 | `azmcp_deploy_plan_get` | ✅ **EXPECTED** |
| 2 | 0.587903 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 3 | 0.499385 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.498575 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 5 | 0.441998 | `azmcp_foundry_models_deploy` | ❌ |

---

## Test 115

**Expected Tool:** `azmcp_eventgrid_events_publish`  
**Prompt:** Publish an event to Event Grid topic <topic_name> using <event_schema> with the following data <event_data>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.755376 | `azmcp_eventgrid_events_publish` | ✅ **EXPECTED** |
| 2 | 0.483208 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.466031 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.355599 | `azmcp_servicebus_topic_details` | ❌ |
| 5 | 0.327844 | `azmcp_eventhubs_namespace_get` | ❌ |

---

## Test 116

**Expected Tool:** `azmcp_eventgrid_events_publish`  
**Prompt:** Publish event to my Event Grid topic <topic_name> with the following events <event_data>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.654879 | `azmcp_eventgrid_events_publish` | ✅ **EXPECTED** |
| 2 | 0.525202 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.510232 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.373812 | `azmcp_servicebus_topic_details` | ❌ |
| 5 | 0.332477 | `azmcp_eventhubs_namespace_get` | ❌ |

---

## Test 117

**Expected Tool:** `azmcp_eventgrid_events_publish`  
**Prompt:** Send an event to Event Grid topic <topic_name> in resource group <resource_group_name> with <event_data>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.600302 | `azmcp_eventgrid_events_publish` | ✅ **EXPECTED** |
| 2 | 0.521240 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.504919 | `azmcp_eventgrid_subscription_list` | ❌ |
| 4 | 0.385359 | `azmcp_eventhubs_namespace_get` | ❌ |
| 5 | 0.353745 | `azmcp_servicebus_topic_details` | ❌ |

---

## Test 118

**Expected Tool:** `azmcp_eventgrid_topic_list`  
**Prompt:** List all Event Grid topics in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.770140 | `azmcp_eventgrid_topic_list` | ✅ **EXPECTED** |
| 2 | 0.745542 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.561862 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.545540 | `azmcp_search_service_list` | ❌ |
| 5 | 0.526138 | `azmcp_subscription_list` | ❌ |

---

## Test 119

**Expected Tool:** `azmcp_eventgrid_topic_list`  
**Prompt:** Show me the Event Grid topics in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.738251 | `azmcp_eventgrid_topic_list` | ✅ **EXPECTED** |
| 2 | 0.737590 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.492572 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.480259 | `azmcp_subscription_list` | ❌ |
| 5 | 0.475105 | `azmcp_search_service_list` | ❌ |

---

## Test 120

**Expected Tool:** `azmcp_eventgrid_topic_list`  
**Prompt:** List all Event Grid topics in subscription <subscription>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.770140 | `azmcp_eventgrid_topic_list` | ✅ **EXPECTED** |
| 2 | 0.721487 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.535326 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.514248 | `azmcp_search_service_list` | ❌ |
| 5 | 0.495987 | `azmcp_subscription_list` | ❌ |

---

## Test 121

**Expected Tool:** `azmcp_eventgrid_topic_list`  
**Prompt:** List all Event Grid topics in resource group <resource_group_name> in subscription <subscription>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.758816 | `azmcp_eventgrid_topic_list` | ✅ **EXPECTED** |
| 2 | 0.704479 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.609175 | `azmcp_group_list` | ❌ |
| 4 | 0.528270 | `azmcp_eventhubs_namespace_get` | ❌ |
| 5 | 0.514613 | `azmcp_workbooks_list` | ❌ |

---

## Test 122

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** Show me all Event Grid subscriptions for topic <topic_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.769190 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.720606 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.498615 | `azmcp_servicebus_topic_details` | ❌ |
| 4 | 0.486216 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 5 | 0.486106 | `azmcp_eventgrid_events_publish` | ❌ |

---

## Test 123

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** List Event Grid subscriptions for topic <topic_name> in subscription <subscription>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.718204 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.709805 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.539977 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 4 | 0.529286 | `azmcp_servicebus_topic_details` | ❌ |
| 5 | 0.477834 | `azmcp_eventgrid_events_publish` | ❌ |

---

## Test 124

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** List Event Grid subscriptions for topic <topic_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.746878 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.746174 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.524919 | `azmcp_group_list` | ❌ |
| 4 | 0.503158 | `azmcp_servicebus_topic_details` | ❌ |
| 5 | 0.490915 | `azmcp_eventhubs_namespace_get` | ❌ |

---

## Test 125

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** Show all Event Grid subscriptions in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.736508 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.659727 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.569254 | `azmcp_subscription_list` | ❌ |
| 4 | 0.537922 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.518857 | `azmcp_search_service_list` | ❌ |

---

## Test 126

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** List all Event Grid subscriptions in subscription <subscription>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.684620 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.656277 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.542388 | `azmcp_subscription_list` | ❌ |
| 4 | 0.521053 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.510115 | `azmcp_group_list` | ❌ |

---

## Test 127

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** Show Event Grid subscriptions in resource group <resource_group_name> in subscription <subscription>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.696175 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.691739 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.557573 | `azmcp_group_list` | ❌ |
| 4 | 0.505026 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.502057 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 128

**Expected Tool:** `azmcp_eventgrid_subscription_list`  
**Prompt:** List Event Grid subscriptions for subscription <subscription> in location <location>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.709768 | `azmcp_eventgrid_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.642095 | `azmcp_eventgrid_topic_list` | ❌ |
| 3 | 0.506697 | `azmcp_subscription_list` | ❌ |
| 4 | 0.476763 | `azmcp_search_service_list` | ❌ |
| 5 | 0.475782 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 129

**Expected Tool:** `azmcp_eventhubs_namespace_get`  
**Prompt:** List all Event Hubs namespaces in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.653507 | `azmcp_eventhubs_namespace_get` | ✅ **EXPECTED** |
| 2 | 0.607372 | `azmcp_kusto_cluster_list` | ❌ |
| 3 | 0.557200 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.556163 | `azmcp_eventgrid_subscription_list` | ❌ |
| 5 | 0.535097 | `azmcp_search_service_list` | ❌ |

---

## Test 130

**Expected Tool:** `azmcp_eventhubs_namespace_get`  
**Prompt:** Get the details of my namespace <namespace_name> in my resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.513154 | `azmcp_eventhubs_namespace_get` | ✅ **EXPECTED** |
| 2 | 0.497399 | `azmcp_servicebus_queue_details` | ❌ |
| 3 | 0.470455 | `azmcp_functionapp_get` | ❌ |
| 4 | 0.466515 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 5 | 0.459491 | `azmcp_sql_db_show` | ❌ |

---

## Test 131

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Describe the function app <function_app_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.660116 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.451613 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.450484 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.406310 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 5 | 0.390048 | `azmcp_mysql_server_list` | ❌ |

---

## Test 132

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Get configuration for function app <function_app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.607276 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.447400 | `azmcp_mysql_server_config_get` | ❌ |
| 3 | 0.424693 | `azmcp_appconfig_account_list` | ❌ |
| 4 | 0.411267 | `azmcp_appconfig_kv_get` | ❌ |
| 5 | 0.400402 | `azmcp_deploy_app_logs_get` | ❌ |

---

## Test 133

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Get function app status for <function_app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.622384 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.478470 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.390689 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 4 | 0.383533 | `azmcp_deploy_app_logs_get` | ❌ |
| 5 | 0.347460 | `azmcp_applens_resource_diagnose` | ❌ |

---

## Test 134

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Get information about my function app <function_app_name> in <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.691058 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.463007 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.432290 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 4 | 0.431690 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.424147 | `azmcp_quota_usage_check` | ❌ |

---

## Test 135

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Retrieve host name and status of function app <function_app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.592791 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.476738 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.409712 | `azmcp_deploy_app_logs_get` | ❌ |
| 4 | 0.392265 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.391480 | `azmcp_sql_server_show` | ❌ |

---

## Test 136

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Show function app details for <function_app_name> in <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.687356 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.449588 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.428715 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.392106 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 5 | 0.368193 | `azmcp_resourcehealth_availability-status_list` | ❌ |

---

## Test 137

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Show me the details for the function app <function_app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.644882 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.430189 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.388678 | `azmcp_storage_account_get` | ❌ |
| 4 | 0.370793 | `azmcp_storage_blob_container_get` | ❌ |
| 5 | 0.368420 | `azmcp_storage_blob_get` | ❌ |

---

## Test 138

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Show plan and region for function app <function_app_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.554980 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.426703 | `azmcp_quota_usage_check` | ❌ |
| 3 | 0.424610 | `azmcp_deploy_app_logs_get` | ❌ |
| 4 | 0.408011 | `azmcp_deploy_plan_get` | ❌ |
| 5 | 0.381629 | `azmcp_deploy_architecture_diagram_generate` | ❌ |

---

## Test 139

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** What is the status of function app <function_app_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.565797 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.473865 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.403665 | `azmcp_deploy_app_logs_get` | ❌ |
| 4 | 0.384131 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.369910 | `azmcp_applens_resource_diagnose` | ❌ |

---

## Test 140

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** List all function apps in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.646561 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.559382 | `azmcp_search_service_list` | ❌ |
| 3 | 0.534930 | `azmcp_subscription_list` | ❌ |
| 4 | 0.529031 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.516745 | `azmcp_cosmos_account_list` | ❌ |

---

## Test 141

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** Show me my Azure function apps  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.560249 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.464985 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.436167 | `azmcp_foundry_agents_list` | ❌ |
| 4 | 0.412646 | `azmcp_search_service_list` | ❌ |
| 5 | 0.411323 | `azmcp_get_bestpractices_get` | ❌ |

---

## Test 142

**Expected Tool:** `azmcp_functionapp_get`  
**Prompt:** What function apps do I have?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.433674 | `azmcp_functionapp_get` | ✅ **EXPECTED** |
| 2 | 0.346619 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.337894 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.284362 | `azmcp_get_bestpractices_get` | ❌ |
| 5 | 0.250920 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 143

**Expected Tool:** `azmcp_keyvault_admin_settings_get`  
**Prompt:** Get the account settings for my key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.604766 | `azmcp_keyvault_admin_settings_get` | ✅ **EXPECTED** |
| 2 | 0.520401 | `azmcp_storage_account_get` | ❌ |
| 3 | 0.496629 | `azmcp_keyvault_key_get` | ❌ |
| 4 | 0.452366 | `azmcp_appconfig_kv_set` | ❌ |
| 5 | 0.448039 | `azmcp_keyvault_secret_get` | ❌ |

---

## Test 144

**Expected Tool:** `azmcp_keyvault_admin_settings_get`  
**Prompt:** Show me the account settings for managed HSM keyvault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.671373 | `azmcp_keyvault_admin_settings_get` | ✅ **EXPECTED** |
| 2 | 0.453590 | `azmcp_storage_account_get` | ❌ |
| 3 | 0.441225 | `azmcp_keyvault_key_get` | ❌ |
| 4 | 0.404666 | `azmcp_appconfig_kv_set` | ❌ |
| 5 | 0.395274 | `azmcp_keyvault_secret_get` | ❌ |

---

## Test 145

**Expected Tool:** `azmcp_keyvault_admin_settings_get`  
**Prompt:** What's the value of the <setting_name> setting in my key vault with name <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.505730 | `azmcp_keyvault_admin_settings_get` | ✅ **EXPECTED** |
| 2 | 0.496524 | `azmcp_appconfig_kv_set` | ❌ |
| 3 | 0.420114 | `azmcp_appconfig_kv_lock_set` | ❌ |
| 4 | 0.419117 | `azmcp_keyvault_key_get` | ❌ |
| 5 | 0.410196 | `azmcp_keyvault_secret_get` | ❌ |

---

## Test 146

**Expected Tool:** `azmcp_keyvault_certificate_create`  
**Prompt:** Create a new certificate called <certificate_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.627610 | `azmcp_keyvault_certificate_create` | ✅ **EXPECTED** |
| 2 | 0.570318 | `azmcp_keyvault_certificate_import` | ❌ |
| 3 | 0.539871 | `azmcp_keyvault_key_create` | ❌ |
| 4 | 0.519218 | `azmcp_keyvault_certificate_get` | ❌ |
| 5 | 0.500047 | `azmcp_keyvault_certificate_list` | ❌ |

---

## Test 147

**Expected Tool:** `azmcp_keyvault_certificate_create`  
**Prompt:** Generate a certificate named <certificate_name> in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.600446 | `azmcp_keyvault_certificate_create` | ✅ **EXPECTED** |
| 2 | 0.561741 | `azmcp_keyvault_certificate_import` | ❌ |
| 3 | 0.522962 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.502143 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.497904 | `azmcp_keyvault_certificate_list` | ❌ |

---

## Test 148

**Expected Tool:** `azmcp_keyvault_certificate_create`  
**Prompt:** Request creation of certificate <certificate_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.573938 | `azmcp_keyvault_certificate_create` | ✅ **EXPECTED** |
| 2 | 0.527759 | `azmcp_keyvault_certificate_import` | ❌ |
| 3 | 0.498278 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.481062 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.469661 | `azmcp_keyvault_certificate_list` | ❌ |

---

## Test 149

**Expected Tool:** `azmcp_keyvault_certificate_create`  
**Prompt:** Provision a new key vault certificate <certificate_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.591820 | `azmcp_keyvault_certificate_create` | ✅ **EXPECTED** |
| 2 | 0.562265 | `azmcp_keyvault_certificate_import` | ❌ |
| 3 | 0.522147 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.502132 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.480039 | `azmcp_keyvault_certificate_list` | ❌ |

---

## Test 150

**Expected Tool:** `azmcp_keyvault_certificate_create`  
**Prompt:** Issue a certificate <certificate_name> in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.622782 | `azmcp_keyvault_certificate_create` | ✅ **EXPECTED** |
| 2 | 0.558532 | `azmcp_keyvault_certificate_import` | ❌ |
| 3 | 0.534503 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.521379 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.464692 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 151

**Expected Tool:** `azmcp_keyvault_certificate_get`  
**Prompt:** Show me the certificate <certificate_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.600625 | `azmcp_keyvault_certificate_get` | ✅ **EXPECTED** |
| 2 | 0.528441 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.519037 | `azmcp_keyvault_certificate_import` | ❌ |
| 4 | 0.499327 | `azmcp_keyvault_certificate_create` | ❌ |
| 5 | 0.486609 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 152

**Expected Tool:** `azmcp_keyvault_certificate_get`  
**Prompt:** Show me the details of the certificate <certificate_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.646098 | `azmcp_keyvault_certificate_get` | ✅ **EXPECTED** |
| 2 | 0.562988 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.514170 | `azmcp_keyvault_secret_get` | ❌ |
| 4 | 0.509462 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.507737 | `azmcp_keyvault_certificate_import` | ❌ |

---

## Test 153

**Expected Tool:** `azmcp_keyvault_certificate_get`  
**Prompt:** Get the certificate <certificate_name> from vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609523 | `azmcp_keyvault_certificate_get` | ✅ **EXPECTED** |
| 2 | 0.515625 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.511186 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.507768 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.474394 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 154

**Expected Tool:** `azmcp_keyvault_certificate_get`  
**Prompt:** Display the certificate details for <certificate_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.647669 | `azmcp_keyvault_certificate_get` | ✅ **EXPECTED** |
| 2 | 0.527400 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.521593 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.509796 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.501988 | `azmcp_keyvault_secret_get` | ❌ |

---

## Test 155

**Expected Tool:** `azmcp_keyvault_certificate_get`  
**Prompt:** Retrieve certificate metadata for <certificate_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.595890 | `azmcp_keyvault_certificate_get` | ✅ **EXPECTED** |
| 2 | 0.527407 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.519040 | `azmcp_keyvault_certificate_import` | ❌ |
| 4 | 0.501279 | `azmcp_keyvault_certificate_create` | ❌ |
| 5 | 0.465111 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 156

**Expected Tool:** `azmcp_keyvault_certificate_import`  
**Prompt:** Import the certificate in file <file_path> into the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.585481 | `azmcp_keyvault_certificate_import` | ✅ **EXPECTED** |
| 2 | 0.420747 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.402599 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.399414 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.352483 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 157

**Expected Tool:** `azmcp_keyvault_certificate_import`  
**Prompt:** Import a certificate into the key vault <key_vault_account_name> using the name <certificate_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.622086 | `azmcp_keyvault_certificate_import` | ✅ **EXPECTED** |
| 2 | 0.504248 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.498726 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.448193 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.419371 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 158

**Expected Tool:** `azmcp_keyvault_certificate_import`  
**Prompt:** Upload certificate file <file_path> to key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.595707 | `azmcp_keyvault_certificate_import` | ✅ **EXPECTED** |
| 2 | 0.453830 | `azmcp_keyvault_certificate_create` | ❌ |
| 3 | 0.452551 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.418293 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.413076 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 159

**Expected Tool:** `azmcp_keyvault_certificate_import`  
**Prompt:** Load certificate <certificate_name> from file <file_path> into vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.619480 | `azmcp_keyvault_certificate_import` | ✅ **EXPECTED** |
| 2 | 0.517804 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.480721 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.444442 | `azmcp_keyvault_certificate_list` | ❌ |
| 5 | 0.381454 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 160

**Expected Tool:** `azmcp_keyvault_certificate_import`  
**Prompt:** Add existing certificate file <file_path> to the key vault <key_vault_account_name> with name <certificate_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.595417 | `azmcp_keyvault_certificate_import` | ✅ **EXPECTED** |
| 2 | 0.452372 | `azmcp_keyvault_certificate_create` | ❌ |
| 3 | 0.441616 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.407786 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.392244 | `azmcp_keyvault_secret_create` | ❌ |

---

## Test 161

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** List all certificates in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.726192 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.583110 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.531988 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.515236 | `azmcp_keyvault_certificate_get` | ❌ |
| 5 | 0.485849 | `azmcp_keyvault_certificate_create` | ❌ |

---

## Test 162

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** Show me the certificates in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.615600 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.522453 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.475156 | `azmcp_keyvault_key_list` | ❌ |
| 4 | 0.461045 | `azmcp_keyvault_certificate_create` | ❌ |
| 5 | 0.448139 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 163

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** What certificates are in the key vault <key_vault_account_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.624771 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.519739 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.510053 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.505534 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.497356 | `azmcp_keyvault_key_list` | ❌ |

---

## Test 164

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** List certificate names in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.672688 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.553990 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.511905 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.507062 | `azmcp_keyvault_certificate_get` | ❌ |
| 5 | 0.492313 | `azmcp_keyvault_certificate_create` | ❌ |

---

## Test 165

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** Enumerate certificates in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.747449 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.594216 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.558771 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.515568 | `azmcp_keyvault_certificate_get` | ❌ |
| 5 | 0.490973 | `azmcp_keyvault_certificate_create` | ❌ |

---

## Test 166

**Expected Tool:** `azmcp_keyvault_certificate_list`  
**Prompt:** Show certificate names in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.639800 | `azmcp_keyvault_certificate_list` | ✅ **EXPECTED** |
| 2 | 0.512475 | `azmcp_keyvault_certificate_get` | ❌ |
| 3 | 0.507572 | `azmcp_keyvault_key_list` | ❌ |
| 4 | 0.482607 | `azmcp_keyvault_certificate_create` | ❌ |
| 5 | 0.464725 | `azmcp_keyvault_secret_list` | ❌ |

---

## Test 167

**Expected Tool:** `azmcp_keyvault_key_create`  
**Prompt:** Create a new key called <key_name> with the RSA type in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.661186 | `azmcp_keyvault_key_create` | ✅ **EXPECTED** |
| 2 | 0.456580 | `azmcp_keyvault_secret_create` | ❌ |
| 3 | 0.451588 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.429614 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.399326 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 168

**Expected Tool:** `azmcp_keyvault_key_create`  
**Prompt:** Generate a key <key_name> with type <key_type> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.640889 | `azmcp_keyvault_key_create` | ✅ **EXPECTED** |
| 2 | 0.428533 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.422671 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.420144 | `azmcp_keyvault_secret_create` | ❌ |
| 5 | 0.405786 | `azmcp_appconfig_kv_set` | ❌ |

---

## Test 169

**Expected Tool:** `azmcp_keyvault_key_create`  
**Prompt:** Create an oct key in the vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.547023 | `azmcp_keyvault_key_create` | ✅ **EXPECTED** |
| 2 | 0.463557 | `azmcp_keyvault_secret_create` | ❌ |
| 3 | 0.447280 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.420366 | `azmcp_keyvault_key_get` | ❌ |
| 5 | 0.404350 | `azmcp_keyvault_certificate_import` | ❌ |

---

## Test 170

**Expected Tool:** `azmcp_keyvault_key_create`  
**Prompt:** Create an RSA key in the vault <key_vault_account_name> with name <key_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.641076 | `azmcp_keyvault_key_create` | ✅ **EXPECTED** |
| 2 | 0.501643 | `azmcp_keyvault_secret_create` | ❌ |
| 3 | 0.491497 | `azmcp_keyvault_certificate_create` | ❌ |
| 4 | 0.464544 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.451021 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 171

**Expected Tool:** `azmcp_keyvault_key_create`  
**Prompt:** Create an EC key with name <key_name> in the vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.571520 | `azmcp_keyvault_key_create` | ✅ **EXPECTED** |
| 2 | 0.443253 | `azmcp_keyvault_certificate_create` | ❌ |
| 3 | 0.434675 | `azmcp_keyvault_secret_create` | ❌ |
| 4 | 0.421721 | `azmcp_keyvault_key_get` | ❌ |
| 5 | 0.400533 | `azmcp_keyvault_certificate_import` | ❌ |

---

## Test 172

**Expected Tool:** `azmcp_keyvault_key_get`  
**Prompt:** Show me the key <key_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.549488 | `azmcp_keyvault_key_get` | ✅ **EXPECTED** |
| 2 | 0.468165 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.452565 | `azmcp_keyvault_key_create` | ❌ |
| 4 | 0.439969 | `azmcp_keyvault_key_list` | ❌ |
| 5 | 0.426545 | `azmcp_keyvault_certificate_get` | ❌ |

---

## Test 173

**Expected Tool:** `azmcp_keyvault_key_get`  
**Prompt:** Show me the details of the key <key_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.629552 | `azmcp_keyvault_key_get` | ✅ **EXPECTED** |
| 2 | 0.532651 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.495957 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.475152 | `azmcp_storage_account_get` | ❌ |
| 5 | 0.456703 | `azmcp_keyvault_key_create` | ❌ |

---

## Test 174

**Expected Tool:** `azmcp_keyvault_key_get`  
**Prompt:** Get the key <key_name> from vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.484645 | `azmcp_keyvault_key_get` | ✅ **EXPECTED** |
| 2 | 0.442960 | `azmcp_keyvault_key_create` | ❌ |
| 3 | 0.409388 | `azmcp_keyvault_secret_get` | ❌ |
| 4 | 0.395467 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.383519 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 175

**Expected Tool:** `azmcp_keyvault_key_get`  
**Prompt:** Display the key details for <key_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.590303 | `azmcp_keyvault_key_get` | ✅ **EXPECTED** |
| 2 | 0.488213 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.460796 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.440938 | `azmcp_storage_account_get` | ❌ |
| 5 | 0.436489 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 176

**Expected Tool:** `azmcp_keyvault_key_get`  
**Prompt:** Retrieve key metadata for <key_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.518886 | `azmcp_keyvault_key_get` | ✅ **EXPECTED** |
| 2 | 0.432732 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 3 | 0.428957 | `azmcp_keyvault_key_create` | ❌ |
| 4 | 0.422536 | `azmcp_keyvault_secret_get` | ❌ |
| 5 | 0.395959 | `azmcp_keyvault_key_list` | ❌ |

---

## Test 177

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** List all keys in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.701448 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.601591 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.587427 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.498721 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.480115 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 178

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** Show me the keys in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.549453 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.506815 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.475553 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.472450 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.455683 | `azmcp_keyvault_secret_get` | ❌ |

---

## Test 179

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** What keys are in the key vault <key_vault_account_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.581970 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.502228 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 3 | 0.501542 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.476470 | `azmcp_keyvault_key_get` | ❌ |
| 5 | 0.472414 | `azmcp_keyvault_secret_list` | ❌ |

---

## Test 180

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** List key names in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.641314 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.559591 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.553553 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.486359 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.475953 | `azmcp_cosmos_account_list` | ❌ |

---

## Test 181

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** Enumerate keys in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.723266 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.611428 | `azmcp_keyvault_certificate_list` | ❌ |
| 3 | 0.611185 | `azmcp_keyvault_secret_list` | ❌ |
| 4 | 0.473874 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.441881 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 182

**Expected Tool:** `azmcp_keyvault_key_list`  
**Prompt:** Show key names in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.570444 | `azmcp_keyvault_key_list` | ✅ **EXPECTED** |
| 2 | 0.501073 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.500177 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.490367 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.489625 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 183

**Expected Tool:** `azmcp_keyvault_secret_create`  
**Prompt:** Create a new secret called <secret_name> with value <secret_value> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.678652 | `azmcp_keyvault_secret_create` | ✅ **EXPECTED** |
| 2 | 0.552825 | `azmcp_keyvault_key_create` | ❌ |
| 3 | 0.512931 | `azmcp_keyvault_secret_get` | ❌ |
| 4 | 0.475056 | `azmcp_keyvault_certificate_create` | ❌ |
| 5 | 0.461580 | `azmcp_appconfig_kv_set` | ❌ |

---

## Test 184

**Expected Tool:** `azmcp_keyvault_secret_create`  
**Prompt:** Set a secret named <secret_name> with value <secret_value> in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.663094 | `azmcp_keyvault_secret_create` | ✅ **EXPECTED** |
| 2 | 0.519601 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.512233 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.458351 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.429785 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 185

**Expected Tool:** `azmcp_keyvault_secret_create`  
**Prompt:** Store secret <secret_name> value <secret_value> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.639897 | `azmcp_keyvault_secret_create` | ✅ **EXPECTED** |
| 2 | 0.509674 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.485203 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.484342 | `azmcp_keyvault_key_create` | ❌ |
| 5 | 0.448995 | `azmcp_appconfig_kv_lock_set` | ❌ |

---

## Test 186

**Expected Tool:** `azmcp_keyvault_secret_create`  
**Prompt:** Add a new version of secret <secret_name> with value <secret_value> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.675145 | `azmcp_keyvault_secret_create` | ✅ **EXPECTED** |
| 2 | 0.499612 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.498022 | `azmcp_keyvault_key_create` | ❌ |
| 4 | 0.479174 | `azmcp_keyvault_certificate_import` | ❌ |
| 5 | 0.458574 | `azmcp_appconfig_kv_set` | ❌ |

---

## Test 187

**Expected Tool:** `azmcp_keyvault_secret_create`  
**Prompt:** Update secret <secret_name> to value <secret_value> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.571612 | `azmcp_keyvault_secret_create` | ✅ **EXPECTED** |
| 2 | 0.513767 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.441223 | `azmcp_appconfig_kv_set` | ❌ |
| 4 | 0.417943 | `azmcp_appconfig_kv_lock_set` | ❌ |
| 5 | 0.408242 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 188

**Expected Tool:** `azmcp_keyvault_secret_get`  
**Prompt:** Show me the secret <secret_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.602769 | `azmcp_keyvault_secret_get` | ✅ **EXPECTED** |
| 2 | 0.504212 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.501397 | `azmcp_keyvault_secret_create` | ❌ |
| 4 | 0.478769 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.439521 | `azmcp_keyvault_certificate_get` | ❌ |

---

## Test 189

**Expected Tool:** `azmcp_keyvault_secret_get`  
**Prompt:** Show me the details of the secret <secret_name> in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.653871 | `azmcp_keyvault_secret_get` | ✅ **EXPECTED** |
| 2 | 0.566786 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.496050 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.485249 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.483567 | `azmcp_storage_account_get` | ❌ |

---

## Test 190

**Expected Tool:** `azmcp_keyvault_secret_get`  
**Prompt:** Get the secret <secret_name> from vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.578479 | `azmcp_keyvault_secret_get` | ✅ **EXPECTED** |
| 2 | 0.492213 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.488705 | `azmcp_keyvault_secret_create` | ❌ |
| 4 | 0.443676 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.424150 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 191

**Expected Tool:** `azmcp_keyvault_secret_get`  
**Prompt:** Display the secret details for <secret_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.649267 | `azmcp_keyvault_secret_get` | ✅ **EXPECTED** |
| 2 | 0.546992 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.492583 | `azmcp_keyvault_certificate_get` | ❌ |
| 4 | 0.491596 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.480354 | `azmcp_keyvault_secret_create` | ❌ |

---

## Test 192

**Expected Tool:** `azmcp_keyvault_secret_get`  
**Prompt:** Retrieve secret metadata for <secret_name> in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.577477 | `azmcp_keyvault_secret_get` | ✅ **EXPECTED** |
| 2 | 0.475443 | `azmcp_keyvault_key_get` | ❌ |
| 3 | 0.466890 | `azmcp_keyvault_secret_create` | ❌ |
| 4 | 0.447602 | `azmcp_keyvault_secret_list` | ❌ |
| 5 | 0.421352 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 193

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** List all secrets in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.701227 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.563736 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.538371 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.499642 | `azmcp_keyvault_secret_get` | ❌ |
| 5 | 0.455456 | `azmcp_cosmos_account_list` | ❌ |

---

## Test 194

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** Show me the secrets in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.555681 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.543861 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.497525 | `azmcp_keyvault_key_get` | ❌ |
| 4 | 0.464661 | `azmcp_keyvault_key_list` | ❌ |
| 5 | 0.453120 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 195

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** What secrets are in the key vault <key_vault_account_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.572540 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.529258 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.493761 | `azmcp_keyvault_key_list` | ❌ |
| 4 | 0.487610 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.475273 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 196

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** List secrets names in vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.624290 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.559681 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.517534 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.479547 | `azmcp_keyvault_secret_get` | ❌ |
| 5 | 0.442932 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 197

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** Enumerate secrets in key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.742358 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.601183 | `azmcp_keyvault_key_list` | ❌ |
| 3 | 0.567842 | `azmcp_keyvault_certificate_list` | ❌ |
| 4 | 0.496127 | `azmcp_keyvault_secret_get` | ❌ |
| 5 | 0.437552 | `azmcp_keyvault_admin_settings_get` | ❌ |

---

## Test 198

**Expected Tool:** `azmcp_keyvault_secret_list`  
**Prompt:** Show secrets names in the key vault <key_vault_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.567110 | `azmcp_keyvault_secret_list` | ✅ **EXPECTED** |
| 2 | 0.522398 | `azmcp_keyvault_secret_get` | ❌ |
| 3 | 0.476309 | `azmcp_keyvault_key_list` | ❌ |
| 4 | 0.462676 | `azmcp_keyvault_secret_create` | ❌ |
| 5 | 0.461326 | `azmcp_keyvault_key_get` | ❌ |

---

## Test 199

**Expected Tool:** `azmcp_aks_cluster_get`  
**Prompt:** Get the configuration of AKS cluster <cluster-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.660885 | `azmcp_aks_cluster_get` | ✅ **EXPECTED** |
| 2 | 0.611431 | `azmcp_aks_cluster_list` | ❌ |
| 3 | 0.579676 | `azmcp_aks_nodepool_get` | ❌ |
| 4 | 0.540767 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.515824 | `azmcp_kusto_cluster_get` | ❌ |

---

## Test 200

**Expected Tool:** `azmcp_aks_cluster_get`  
**Prompt:** Show me the details of AKS cluster <cluster-name> in resource group <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.666912 | `azmcp_aks_cluster_get` | ✅ **EXPECTED** |
| 2 | 0.589101 | `azmcp_aks_cluster_list` | ❌ |
| 3 | 0.570594 | `azmcp_kusto_cluster_get` | ❌ |
| 4 | 0.545820 | `azmcp_aks_nodepool_get` | ❌ |
| 5 | 0.530314 | `azmcp_aks_nodepool_list` | ❌ |

---

## Test 201

**Expected Tool:** `azmcp_aks_cluster_get`  
**Prompt:** Show me the network configuration for AKS cluster <cluster-name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.567345 | `azmcp_aks_cluster_get` | ✅ **EXPECTED** |
| 2 | 0.563029 | `azmcp_aks_cluster_list` | ❌ |
| 3 | 0.493940 | `azmcp_aks_nodepool_list` | ❌ |
| 4 | 0.486040 | `azmcp_aks_nodepool_get` | ❌ |
| 5 | 0.437092 | `azmcp_kusto_cluster_get` | ❌ |

---

## Test 202

**Expected Tool:** `azmcp_aks_cluster_get`  
**Prompt:** What are the details of my AKS cluster <cluster-name> in <resource-group>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.661417 | `azmcp_aks_cluster_get` | ✅ **EXPECTED** |
| 2 | 0.578662 | `azmcp_aks_cluster_list` | ❌ |
| 3 | 0.563549 | `azmcp_aks_nodepool_get` | ❌ |
| 4 | 0.534089 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.526600 | `azmcp_kusto_cluster_get` | ❌ |

---

## Test 203

**Expected Tool:** `azmcp_aks_cluster_list`  
**Prompt:** List all AKS clusters in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.801067 | `azmcp_aks_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.749416 | `azmcp_kusto_cluster_list` | ❌ |
| 3 | 0.594509 | `azmcp_aks_nodepool_list` | ❌ |
| 4 | 0.568251 | `azmcp_kusto_database_list` | ❌ |
| 5 | 0.562043 | `azmcp_search_service_list` | ❌ |

---

## Test 204

**Expected Tool:** `azmcp_aks_cluster_list`  
**Prompt:** Show me my Azure Kubernetes Service clusters  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.608056 | `azmcp_aks_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.586661 | `azmcp_kusto_cluster_list` | ❌ |
| 3 | 0.536458 | `azmcp_aks_cluster_get` | ❌ |
| 4 | 0.500890 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.492760 | `azmcp_kusto_cluster_get` | ❌ |

---

## Test 205

**Expected Tool:** `azmcp_aks_cluster_list`  
**Prompt:** What AKS clusters do I have?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.623896 | `azmcp_aks_cluster_list` | ✅ **EXPECTED** |
| 2 | 0.538749 | `azmcp_aks_nodepool_list` | ❌ |
| 3 | 0.530108 | `azmcp_aks_cluster_get` | ❌ |
| 4 | 0.526756 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.466749 | `azmcp_aks_nodepool_get` | ❌ |

---

## Test 206

**Expected Tool:** `azmcp_aks_nodepool_get`  
**Prompt:** Get details for nodepool <nodepool-name> in AKS cluster <cluster-name> in <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.753921 | `azmcp_aks_nodepool_get` | ✅ **EXPECTED** |
| 2 | 0.699421 | `azmcp_aks_nodepool_list` | ❌ |
| 3 | 0.597341 | `azmcp_aks_cluster_get` | ❌ |
| 4 | 0.516008 | `azmcp_kusto_cluster_get` | ❌ |
| 5 | 0.498590 | `azmcp_aks_cluster_list` | ❌ |

---

## Test 207

**Expected Tool:** `azmcp_aks_nodepool_get`  
**Prompt:** Show me the configuration for nodepool <nodepool-name> in AKS cluster <cluster-name> in resource group <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.678220 | `azmcp_aks_nodepool_get` | ✅ **EXPECTED** |
| 2 | 0.640161 | `azmcp_aks_nodepool_list` | ❌ |
| 3 | 0.481459 | `azmcp_aks_cluster_get` | ❌ |
| 4 | 0.458614 | `azmcp_sql_elastic-pool_list` | ❌ |
| 5 | 0.446095 | `azmcp_aks_cluster_list` | ❌ |

---

## Test 208

**Expected Tool:** `azmcp_aks_nodepool_get`  
**Prompt:** What is the setup of nodepool <nodepool-name> for AKS cluster <cluster-name> in <resource-group>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.599506 | `azmcp_aks_nodepool_get` | ✅ **EXPECTED** |
| 2 | 0.582325 | `azmcp_aks_nodepool_list` | ❌ |
| 3 | 0.412125 | `azmcp_aks_cluster_get` | ❌ |
| 4 | 0.391590 | `azmcp_aks_cluster_list` | ❌ |
| 5 | 0.385236 | `azmcp_virtualdesktop_hostpool_list` | ❌ |

---

## Test 209

**Expected Tool:** `azmcp_aks_nodepool_list`  
**Prompt:** List nodepools for AKS cluster <cluster-name> in <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.694117 | `azmcp_aks_nodepool_list` | ✅ **EXPECTED** |
| 2 | 0.615516 | `azmcp_aks_nodepool_get` | ❌ |
| 3 | 0.531972 | `azmcp_aks_cluster_list` | ❌ |
| 4 | 0.506704 | `azmcp_virtualdesktop_hostpool_list` | ❌ |
| 5 | 0.500749 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 210

**Expected Tool:** `azmcp_aks_nodepool_list`  
**Prompt:** Show me the nodepool list for AKS cluster <cluster-name> in <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.712254 | `azmcp_aks_nodepool_list` | ✅ **EXPECTED** |
| 2 | 0.644448 | `azmcp_aks_nodepool_get` | ❌ |
| 3 | 0.547311 | `azmcp_aks_cluster_list` | ❌ |
| 4 | 0.510279 | `azmcp_sql_elastic-pool_list` | ❌ |
| 5 | 0.509677 | `azmcp_virtualdesktop_hostpool_list` | ❌ |

---

## Test 211

**Expected Tool:** `azmcp_aks_nodepool_list`  
**Prompt:** What nodepools do I have for AKS cluster <cluster-name> in <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.623138 | `azmcp_aks_nodepool_list` | ✅ **EXPECTED** |
| 2 | 0.580535 | `azmcp_aks_nodepool_get` | ❌ |
| 3 | 0.453744 | `azmcp_aks_cluster_list` | ❌ |
| 4 | 0.443942 | `azmcp_virtualdesktop_hostpool_list` | ❌ |
| 5 | 0.433006 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 212

**Expected Tool:** `azmcp_loadtesting_test_create`  
**Prompt:** Create a basic URL test using the following endpoint URL <test-url> that runs for 30 minutes with 45 virtual users. The test name is <sample-name> with the test id <test-id> and the load testing resource is <load-test-resource> in the resource group <resource-group> in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.585388 | `azmcp_loadtesting_test_create` | ✅ **EXPECTED** |
| 2 | 0.531496 | `azmcp_loadtesting_testresource_create` | ❌ |
| 3 | 0.508759 | `azmcp_loadtesting_testrun_create` | ❌ |
| 4 | 0.413857 | `azmcp_loadtesting_testresource_list` | ❌ |
| 5 | 0.394664 | `azmcp_loadtesting_testrun_get` | ❌ |

---

## Test 213

**Expected Tool:** `azmcp_loadtesting_test_get`  
**Prompt:** Get the load test with id <test-id> in the load test resource <test-resource> in resource group <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.642420 | `azmcp_loadtesting_test_get` | ✅ **EXPECTED** |
| 2 | 0.608881 | `azmcp_loadtesting_testresource_list` | ❌ |
| 3 | 0.575806 | `azmcp_loadtesting_testresource_create` | ❌ |
| 4 | 0.534194 | `azmcp_loadtesting_testrun_get` | ❌ |
| 5 | 0.473363 | `azmcp_loadtesting_testrun_create` | ❌ |

---

## Test 214

**Expected Tool:** `azmcp_loadtesting_testresource_create`  
**Prompt:** Create a load test resource <load-test-resource-name> in the resource group <resource-group> in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.717487 | `azmcp_loadtesting_testresource_create` | ✅ **EXPECTED** |
| 2 | 0.596828 | `azmcp_loadtesting_testresource_list` | ❌ |
| 3 | 0.514437 | `azmcp_loadtesting_test_create` | ❌ |
| 4 | 0.476716 | `azmcp_loadtesting_testrun_create` | ❌ |
| 5 | 0.443117 | `azmcp_loadtesting_test_get` | ❌ |

---

## Test 215

**Expected Tool:** `azmcp_loadtesting_testresource_list`  
**Prompt:** List all load testing resources in the resource group <resource-group> in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.738027 | `azmcp_loadtesting_testresource_list` | ✅ **EXPECTED** |
| 2 | 0.592783 | `azmcp_loadtesting_testresource_create` | ❌ |
| 3 | 0.577408 | `azmcp_group_list` | ❌ |
| 4 | 0.565431 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 5 | 0.561537 | `azmcp_resourcehealth_availability-status_list` | ❌ |

---

## Test 216

**Expected Tool:** `azmcp_loadtesting_testrun_create`  
**Prompt:** Create a test run using the id <testrun-id> for test <test-id> in the load testing resource <load-testing-resource> in resource group <resource-group>. Use the name of test run <display-name> and description as <description>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.621862 | `azmcp_loadtesting_testrun_create` | ✅ **EXPECTED** |
| 2 | 0.592627 | `azmcp_loadtesting_testresource_create` | ❌ |
| 3 | 0.540789 | `azmcp_loadtesting_test_create` | ❌ |
| 4 | 0.530882 | `azmcp_loadtesting_testrun_update` | ❌ |
| 5 | 0.488142 | `azmcp_loadtesting_testrun_get` | ❌ |

---

## Test 217

**Expected Tool:** `azmcp_loadtesting_testrun_get`  
**Prompt:** Get the load test run with id <testrun-id> in the load test resource <test-resource> in resource group <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.625332 | `azmcp_loadtesting_test_get` | ❌ |
| 2 | 0.603066 | `azmcp_loadtesting_testresource_list` | ❌ |
| 3 | 0.568405 | `azmcp_loadtesting_testrun_get` | ✅ **EXPECTED** |
| 4 | 0.563113 | `azmcp_loadtesting_testresource_create` | ❌ |
| 5 | 0.535218 | `azmcp_loadtesting_testrun_create` | ❌ |

---

## Test 218

**Expected Tool:** `azmcp_loadtesting_testrun_list`  
**Prompt:** Get all the load test runs for the test with id <test-id> in the load test resource <test-resource> in resource group <resource-group>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.615977 | `azmcp_loadtesting_testresource_list` | ❌ |
| 2 | 0.606058 | `azmcp_loadtesting_test_get` | ❌ |
| 3 | 0.569145 | `azmcp_loadtesting_testrun_get` | ❌ |
| 4 | 0.565230 | `azmcp_loadtesting_testrun_list` | ✅ **EXPECTED** |
| 5 | 0.536259 | `azmcp_loadtesting_testresource_create` | ❌ |

---

## Test 219

**Expected Tool:** `azmcp_loadtesting_testrun_update`  
**Prompt:** Update a test run display name as <display-name> for the id <testrun-id> for test <test-id> in the load testing resource <load-testing-resource> in resource group <resource-group>.  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.659812 | `azmcp_loadtesting_testrun_update` | ✅ **EXPECTED** |
| 2 | 0.509252 | `azmcp_loadtesting_testrun_create` | ❌ |
| 3 | 0.454745 | `azmcp_loadtesting_testrun_get` | ❌ |
| 4 | 0.443828 | `azmcp_loadtesting_test_get` | ❌ |
| 5 | 0.422154 | `azmcp_loadtesting_testresource_create` | ❌ |

---

## Test 220

**Expected Tool:** `azmcp_grafana_list`  
**Prompt:** List all Azure Managed Grafana in one subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.599427 | `azmcp_kusto_cluster_list` | ❌ |
| 2 | 0.578892 | `azmcp_grafana_list` | ✅ **EXPECTED** |
| 3 | 0.551851 | `azmcp_search_service_list` | ❌ |
| 4 | 0.550372 | `azmcp_subscription_list` | ❌ |
| 5 | 0.513083 | `azmcp_monitor_workspace_list` | ❌ |

---

## Test 221

**Expected Tool:** `azmcp_azuremanagedlustre_filesystem_list`  
**Prompt:** List the Azure Managed Lustre filesystems in my subscription <subscription_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.750286 | `azmcp_azuremanagedlustre_filesystem_list` | ✅ **EXPECTED** |
| 2 | 0.631770 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 3 | 0.562377 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.513156 | `azmcp_search_service_list` | ❌ |
| 5 | 0.509911 | `azmcp_kusto_database_list` | ❌ |

---

## Test 222

**Expected Tool:** `azmcp_azuremanagedlustre_filesystem_list`  
**Prompt:** List the Azure Managed Lustre filesystems in my resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.743638 | `azmcp_azuremanagedlustre_filesystem_list` | ✅ **EXPECTED** |
| 2 | 0.613217 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 3 | 0.519874 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 4 | 0.514120 | `azmcp_mysql_server_list` | ❌ |
| 5 | 0.492115 | `azmcp_acr_registry_repository_list` | ❌ |

---

## Test 223

**Expected Tool:** `azmcp_azuremanagedlustre_filesystem_required-subnet-size`  
**Prompt:** Tell me how many IP addresses I need for <filesystem_size> of <amlfs_sku>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.646978 | `azmcp_azuremanagedlustre_filesystem_required-subnet-size` | ✅ **EXPECTED** |
| 2 | 0.450098 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |
| 3 | 0.327359 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 4 | 0.265578 | `azmcp_cloudarchitect_design` | ❌ |
| 5 | 0.204654 | `azmcp_mysql_server_list` | ❌ |

---

## Test 224

**Expected Tool:** `azmcp_azuremanagedlustre_filesystem_sku_get`  
**Prompt:** List the Azure Managed Lustre SKUs available in <location>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.836071 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ✅ **EXPECTED** |
| 2 | 0.625869 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |
| 3 | 0.473878 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.453801 | `azmcp_storage_account_get` | ❌ |
| 5 | 0.444792 | `azmcp_search_service_list` | ❌ |

---

## Test 225

**Expected Tool:** `azmcp_marketplace_product_get`  
**Prompt:** Get details about marketplace product <product_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.570145 | `azmcp_marketplace_product_get` | ✅ **EXPECTED** |
| 2 | 0.477522 | `azmcp_marketplace_product_list` | ❌ |
| 3 | 0.353256 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 4 | 0.333160 | `azmcp_servicebus_topic_details` | ❌ |
| 5 | 0.330935 | `azmcp_servicebus_queue_details` | ❌ |

---

## Test 226

**Expected Tool:** `azmcp_marketplace_product_list`  
**Prompt:** Search for Microsoft products in the marketplace  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.527077 | `azmcp_marketplace_product_list` | ✅ **EXPECTED** |
| 2 | 0.443133 | `azmcp_marketplace_product_get` | ❌ |
| 3 | 0.343549 | `azmcp_search_service_list` | ❌ |
| 4 | 0.330537 | `azmcp_foundry_models_list` | ❌ |
| 5 | 0.328676 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |

---

## Test 227

**Expected Tool:** `azmcp_marketplace_product_list`  
**Prompt:** Show me marketplace products from publisher <publisher_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.461616 | `azmcp_marketplace_product_list` | ✅ **EXPECTED** |
| 2 | 0.385167 | `azmcp_marketplace_product_get` | ❌ |
| 3 | 0.308758 | `azmcp_foundry_models_list` | ❌ |
| 4 | 0.260387 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 5 | 0.247908 | `azmcp_eventgrid_topic_list` | ❌ |

---

## Test 228

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure code generation best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.646844 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.635406 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.586907 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.531727 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.490235 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 229

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure deployment best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.600903 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.548542 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.541091 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.516852 | `azmcp_deploy_plan_get` | ❌ |
| 5 | 0.516443 | `azmcp_deploy_pipeline_guidance_get` | ❌ |

---

## Test 230

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.625298 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.594371 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.518711 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.465669 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.450724 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 231

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure Functions code generation best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.624287 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.570498 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.523057 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.494040 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.445405 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 232

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure Functions deployment best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.581850 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.497350 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 3 | 0.495659 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.486886 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 5 | 0.474511 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 233

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure Functions best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.610986 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.532790 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.487322 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.458060 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.413150 | `azmcp_functionapp_get` | ❌ |

---

## Test 234

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** Get the latest Azure Static Web Apps best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.557862 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.513262 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.505123 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.483705 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.421581 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 235

**Expected Tool:** `azmcp_get_bestpractices_get`  
**Prompt:** What are azure function best practices?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.582541 | `azmcp_get_bestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.500368 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.472112 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.433134 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.432087 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 236

**Expected Tool:** `azmcp_monitor_healthmodels_entity_gethealth`  
**Prompt:** Show me the health status of entity <entity_id> in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.497983 | `azmcp_monitor_healthmodels_entity_gethealth` | ✅ **EXPECTED** |
| 2 | 0.492252 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.472218 | `azmcp_monitor_workspace_list` | ❌ |
| 4 | 0.468124 | `azmcp_monitor_table_list` | ❌ |
| 5 | 0.467913 | `azmcp_monitor_workspace_log_query` | ❌ |

---

## Test 237

**Expected Tool:** `azmcp_monitor_metrics_definitions`  
**Prompt:** Get metric definitions for <resource_type> <resource_name> from the namespace  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.592640 | `azmcp_monitor_metrics_definitions` | ✅ **EXPECTED** |
| 2 | 0.424141 | `azmcp_monitor_metrics_query` | ❌ |
| 3 | 0.332661 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.332369 | `azmcp_monitor_table_type_list` | ❌ |
| 5 | 0.315476 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |

---

## Test 238

**Expected Tool:** `azmcp_monitor_metrics_definitions`  
**Prompt:** Show me all available metrics and their definitions for storage account <account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.589859 | `azmcp_storage_account_get` | ❌ |
| 2 | 0.587736 | `azmcp_monitor_metrics_definitions` | ✅ **EXPECTED** |
| 3 | 0.551156 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.485326 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 5 | 0.473336 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |

---

## Test 239

**Expected Tool:** `azmcp_monitor_metrics_definitions`  
**Prompt:** What metric definitions are available for the Application Insights resource <resource_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.633173 | `azmcp_monitor_metrics_definitions` | ✅ **EXPECTED** |
| 2 | 0.495513 | `azmcp_monitor_metrics_query` | ❌ |
| 3 | 0.398890 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.383302 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.370826 | `azmcp_monitor_table_type_list` | ❌ |

---

## Test 240

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** Analyze the performance trends and response times for Application Insights resource <resource_name> over the last <time_period>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.555377 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.464816 | `azmcp_applens_resource_diagnose` | ❌ |
| 3 | 0.447576 | `azmcp_monitor_resource_log_query` | ❌ |
| 4 | 0.433777 | `azmcp_loadtesting_testrun_get` | ❌ |
| 5 | 0.428883 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 241

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** Check the availability metrics for my Application Insights resource <resource_name> for the last <time_period>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.557830 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.509377 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.460552 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 4 | 0.455904 | `azmcp_quota_usage_check` | ❌ |
| 5 | 0.438233 | `azmcp_monitor_metrics_definitions` | ❌ |

---

## Test 242

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** Get the <aggregation_type> <metric_name> metric for <resource_type> <resource_name> over the last <time_period> with intervals  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.461249 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.390029 | `azmcp_monitor_metrics_definitions` | ❌ |
| 3 | 0.340219 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.306322 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.301852 | `azmcp_monitor_resource_log_query` | ❌ |

---

## Test 243

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** Investigate error rates and failed requests for Application Insights resource <resource_name> for the last <time_period>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.492138 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.448207 | `azmcp_applens_resource_diagnose` | ❌ |
| 3 | 0.419995 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.415814 | `azmcp_monitor_resource_log_query` | ❌ |
| 5 | 0.412184 | `azmcp_resourcehealth_service-health-events_list` | ❌ |

---

## Test 244

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** Query the <metric_name> metric for <resource_type> <resource_name> for the last <time_period>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.525585 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.384482 | `azmcp_monitor_metrics_definitions` | ❌ |
| 3 | 0.376806 | `azmcp_monitor_resource_log_query` | ❌ |
| 4 | 0.367167 | `azmcp_monitor_workspace_log_query` | ❌ |
| 5 | 0.330628 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 245

**Expected Tool:** `azmcp_monitor_metrics_query`  
**Prompt:** What's the request per second rate for my Application Insights resource <resource_name> over the last <time_period>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.480140 | `azmcp_monitor_metrics_query` | ✅ **EXPECTED** |
| 2 | 0.388498 | `azmcp_applens_resource_diagnose` | ❌ |
| 3 | 0.368490 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.363412 | `azmcp_quota_usage_check` | ❌ |
| 5 | 0.350507 | `azmcp_monitor_resource_log_query` | ❌ |

---

## Test 246

**Expected Tool:** `azmcp_monitor_resource_log_query`  
**Prompt:** Show me the logs for the past hour for the resource <resource_name> in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.594068 | `azmcp_monitor_workspace_log_query` | ❌ |
| 2 | 0.579846 | `azmcp_monitor_resource_log_query` | ✅ **EXPECTED** |
| 3 | 0.485633 | `azmcp_deploy_app_logs_get` | ❌ |
| 4 | 0.469703 | `azmcp_monitor_metrics_query` | ❌ |
| 5 | 0.443464 | `azmcp_monitor_workspace_list` | ❌ |

---

## Test 247

**Expected Tool:** `azmcp_monitor_table_list`  
**Prompt:** List all tables in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.851075 | `azmcp_monitor_table_list` | ✅ **EXPECTED** |
| 2 | 0.725693 | `azmcp_monitor_table_type_list` | ❌ |
| 3 | 0.620384 | `azmcp_monitor_workspace_list` | ❌ |
| 4 | 0.541928 | `azmcp_kusto_table_list` | ❌ |
| 5 | 0.534829 | `azmcp_mysql_table_list` | ❌ |

---

## Test 248

**Expected Tool:** `azmcp_monitor_table_list`  
**Prompt:** Show me the tables in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.798422 | `azmcp_monitor_table_list` | ✅ **EXPECTED** |
| 2 | 0.700724 | `azmcp_monitor_table_type_list` | ❌ |
| 3 | 0.600222 | `azmcp_monitor_workspace_list` | ❌ |
| 4 | 0.497302 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.487607 | `azmcp_grafana_list` | ❌ |

---

## Test 249

**Expected Tool:** `azmcp_monitor_table_type_list`  
**Prompt:** List all available table types in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.881468 | `azmcp_monitor_table_type_list` | ✅ **EXPECTED** |
| 2 | 0.765702 | `azmcp_monitor_table_list` | ❌ |
| 3 | 0.569929 | `azmcp_monitor_workspace_list` | ❌ |
| 4 | 0.504683 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.477280 | `azmcp_grafana_list` | ❌ |

---

## Test 250

**Expected Tool:** `azmcp_monitor_table_type_list`  
**Prompt:** Show me the available table types in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.843110 | `azmcp_monitor_table_type_list` | ✅ **EXPECTED** |
| 2 | 0.736837 | `azmcp_monitor_table_list` | ❌ |
| 3 | 0.576747 | `azmcp_monitor_workspace_list` | ❌ |
| 4 | 0.481189 | `azmcp_mysql_table_list` | ❌ |
| 5 | 0.475734 | `azmcp_grafana_list` | ❌ |

---

## Test 251

**Expected Tool:** `azmcp_monitor_workspace_list`  
**Prompt:** List all Log Analytics workspaces in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.813923 | `azmcp_monitor_workspace_list` | ✅ **EXPECTED** |
| 2 | 0.680201 | `azmcp_grafana_list` | ❌ |
| 3 | 0.660135 | `azmcp_monitor_table_list` | ❌ |
| 4 | 0.610623 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.600802 | `azmcp_search_service_list` | ❌ |

---

## Test 252

**Expected Tool:** `azmcp_monitor_workspace_list`  
**Prompt:** Show me my Log Analytics workspaces  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.656249 | `azmcp_monitor_workspace_list` | ✅ **EXPECTED** |
| 2 | 0.585436 | `azmcp_monitor_table_list` | ❌ |
| 3 | 0.531093 | `azmcp_monitor_table_type_list` | ❌ |
| 4 | 0.518254 | `azmcp_grafana_list` | ❌ |
| 5 | 0.485219 | `azmcp_deploy_app_logs_get` | ❌ |

---

## Test 253

**Expected Tool:** `azmcp_monitor_workspace_list`  
**Prompt:** Show me the Log Analytics workspaces in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.733016 | `azmcp_monitor_workspace_list` | ✅ **EXPECTED** |
| 2 | 0.601481 | `azmcp_grafana_list` | ❌ |
| 3 | 0.580261 | `azmcp_monitor_table_list` | ❌ |
| 4 | 0.522749 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.521287 | `azmcp_monitor_table_type_list` | ❌ |

---

## Test 254

**Expected Tool:** `azmcp_monitor_workspace_log_query`  
**Prompt:** Show me the logs for the past hour in the Log Analytics workspace <workspace_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.591648 | `azmcp_monitor_workspace_log_query` | ✅ **EXPECTED** |
| 2 | 0.498269 | `azmcp_deploy_app_logs_get` | ❌ |
| 3 | 0.494462 | `azmcp_monitor_resource_log_query` | ❌ |
| 4 | 0.485984 | `azmcp_monitor_table_list` | ❌ |
| 5 | 0.483358 | `azmcp_monitor_workspace_list` | ❌ |

---

## Test 255

**Expected Tool:** `azmcp_datadog_monitoredresources_list`  
**Prompt:** List all monitored resources in the Datadog resource <resource_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.668982 | `azmcp_datadog_monitoredresources_list` | ✅ **EXPECTED** |
| 2 | 0.413173 | `azmcp_monitor_metrics_query` | ❌ |
| 3 | 0.401731 | `azmcp_grafana_list` | ❌ |
| 4 | 0.393310 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.386685 | `azmcp_monitor_metrics_definitions` | ❌ |

---

## Test 256

**Expected Tool:** `azmcp_datadog_monitoredresources_list`  
**Prompt:** Show me the monitored resources in the Datadog resource <resource_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.624179 | `azmcp_datadog_monitoredresources_list` | ✅ **EXPECTED** |
| 2 | 0.443481 | `azmcp_monitor_metrics_query` | ❌ |
| 3 | 0.371017 | `azmcp_grafana_list` | ❌ |
| 4 | 0.370685 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.363132 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 257

**Expected Tool:** `azmcp_extension_azqr`  
**Prompt:** Check my Azure subscription for any compliance issues or recommendations  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.533164 | `azmcp_quota_usage_check` | ❌ |
| 2 | 0.481143 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 3 | 0.476826 | `azmcp_extension_azqr` | ✅ **EXPECTED** |
| 4 | 0.471499 | `azmcp_subscription_list` | ❌ |
| 5 | 0.468362 | `azmcp_applens_resource_diagnose` | ❌ |

---

## Test 258

**Expected Tool:** `azmcp_extension_azqr`  
**Prompt:** Provide compliance recommendations for my current Azure subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.532792 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 2 | 0.492863 | `azmcp_get_bestpractices_get` | ❌ |
| 3 | 0.476164 | `azmcp_applicationinsights_recommendation_list` | ❌ |
| 4 | 0.473365 | `azmcp_deploy_iac_rules_get` | ❌ |
| 5 | 0.464604 | `azmcp_cloudarchitect_design` | ❌ |

---

## Test 259

**Expected Tool:** `azmcp_extension_azqr`  
**Prompt:** Scan my Azure subscription for compliance recommendations  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.536955 | `azmcp_azureterraformbestpractices_get` | ❌ |
| 2 | 0.516990 | `azmcp_extension_azqr` | ✅ **EXPECTED** |
| 3 | 0.515027 | `azmcp_applicationinsights_recommendation_list` | ❌ |
| 4 | 0.504705 | `azmcp_quota_usage_check` | ❌ |
| 5 | 0.494871 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 260

**Expected Tool:** `azmcp_quota_region_availability_list`  
**Prompt:** Show me the available regions for these resource types <resource_types>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.590878 | `azmcp_quota_region_availability_list` | ✅ **EXPECTED** |
| 2 | 0.413274 | `azmcp_quota_usage_check` | ❌ |
| 3 | 0.372921 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 4 | 0.369855 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 5 | 0.361422 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 261

**Expected Tool:** `azmcp_quota_usage_check`  
**Prompt:** Check usage information for <resource_type> in region <region>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609384 | `azmcp_quota_usage_check` | ✅ **EXPECTED** |
| 2 | 0.491273 | `azmcp_quota_region_availability_list` | ❌ |
| 3 | 0.398833 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 4 | 0.384019 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.357672 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |

---

## Test 262

**Expected Tool:** `azmcp_role_assignment_list`  
**Prompt:** List all available role assignments in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.645259 | `azmcp_role_assignment_list` | ✅ **EXPECTED** |
| 2 | 0.539761 | `azmcp_subscription_list` | ❌ |
| 3 | 0.483988 | `azmcp_group_list` | ❌ |
| 4 | 0.478700 | `azmcp_grafana_list` | ❌ |
| 5 | 0.471426 | `azmcp_cosmos_account_list` | ❌ |

---

## Test 263

**Expected Tool:** `azmcp_role_assignment_list`  
**Prompt:** Show me the available role assignments in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609705 | `azmcp_role_assignment_list` | ✅ **EXPECTED** |
| 2 | 0.514696 | `azmcp_subscription_list` | ❌ |
| 3 | 0.456956 | `azmcp_grafana_list` | ❌ |
| 4 | 0.449174 | `azmcp_eventgrid_subscription_list` | ❌ |
| 5 | 0.435201 | `azmcp_monitor_workspace_list` | ❌ |

---

## Test 264

**Expected Tool:** `azmcp_redis_cache_accesspolicy_list`  
**Prompt:** List all access policies in the Redis Cache <cache_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.757057 | `azmcp_redis_cache_accesspolicy_list` | ✅ **EXPECTED** |
| 2 | 0.567861 | `azmcp_redis_list` | ❌ |
| 3 | 0.377554 | `azmcp_redis_cluster_database_list` | ❌ |
| 4 | 0.322930 | `azmcp_mysql_database_list` | ❌ |
| 5 | 0.312373 | `azmcp_cosmos_account_list` | ❌ |

---

## Test 265

**Expected Tool:** `azmcp_redis_cache_accesspolicy_list`  
**Prompt:** Show me the access policies in the Redis Cache <cache_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.713839 | `azmcp_redis_cache_accesspolicy_list` | ✅ **EXPECTED** |
| 2 | 0.566769 | `azmcp_redis_list` | ❌ |
| 3 | 0.338856 | `azmcp_redis_cluster_database_list` | ❌ |
| 4 | 0.293651 | `azmcp_keyvault_admin_settings_get` | ❌ |
| 5 | 0.283725 | `azmcp_mysql_database_list` | ❌ |

---

## Test 266

**Expected Tool:** `azmcp_redis_list`  
**Prompt:** List all Redis Caches in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.797904 | `azmcp_redis_list` | ✅ **EXPECTED** |
| 2 | 0.509917 | `azmcp_kusto_cluster_list` | ❌ |
| 3 | 0.501880 | `azmcp_redis_cache_accesspolicy_list` | ❌ |
| 4 | 0.495048 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.472307 | `azmcp_grafana_list` | ❌ |

---

## Test 267

**Expected Tool:** `azmcp_redis_list`  
**Prompt:** Show me my Redis Caches  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.652892 | `azmcp_redis_list` | ✅ **EXPECTED** |
| 2 | 0.450387 | `azmcp_redis_cache_accesspolicy_list` | ❌ |
| 3 | 0.401224 | `azmcp_redis_cluster_database_list` | ❌ |
| 4 | 0.302323 | `azmcp_mysql_database_list` | ❌ |
| 5 | 0.283598 | `azmcp_postgres_database_list` | ❌ |

---

## Test 268

**Expected Tool:** `azmcp_redis_list`  
**Prompt:** Show me the Redis Caches in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.759411 | `azmcp_redis_list` | ✅ **EXPECTED** |
| 2 | 0.461603 | `azmcp_redis_cache_accesspolicy_list` | ❌ |
| 3 | 0.434924 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.427325 | `azmcp_grafana_list` | ❌ |
| 5 | 0.422248 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 269

**Expected Tool:** `azmcp_redis_cluster_database_list`  
**Prompt:** List all databases in the Redis Cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.752893 | `azmcp_redis_cluster_database_list` | ✅ **EXPECTED** |
| 2 | 0.618454 | `azmcp_kusto_database_list` | ❌ |
| 3 | 0.548268 | `azmcp_postgres_database_list` | ❌ |
| 4 | 0.538403 | `azmcp_cosmos_database_list` | ❌ |
| 5 | 0.532041 | `azmcp_redis_list` | ❌ |

---

## Test 270

**Expected Tool:** `azmcp_redis_cluster_database_list`  
**Prompt:** Show me the databases in the Redis Cluster <cluster_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.721488 | `azmcp_redis_cluster_database_list` | ✅ **EXPECTED** |
| 2 | 0.560293 | `azmcp_kusto_database_list` | ❌ |
| 3 | 0.523476 | `azmcp_redis_list` | ❌ |
| 4 | 0.490987 | `azmcp_mysql_database_list` | ❌ |
| 5 | 0.481618 | `azmcp_cosmos_database_list` | ❌ |

---

## Test 271

**Expected Tool:** `azmcp_group_list`  
**Prompt:** List all resource groups in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.755935 | `azmcp_group_list` | ✅ **EXPECTED** |
| 2 | 0.566552 | `azmcp_workbooks_list` | ❌ |
| 3 | 0.552464 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 4 | 0.546182 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.542878 | `azmcp_grafana_list` | ❌ |

---

## Test 272

**Expected Tool:** `azmcp_group_list`  
**Prompt:** Show me my resource groups  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.529504 | `azmcp_group_list` | ✅ **EXPECTED** |
| 2 | 0.463595 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 3 | 0.462391 | `azmcp_mysql_server_list` | ❌ |
| 4 | 0.459340 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.453960 | `azmcp_workbooks_list` | ❌ |

---

## Test 273

**Expected Tool:** `azmcp_group_list`  
**Prompt:** Show me the resource groups in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.665771 | `azmcp_group_list` | ✅ **EXPECTED** |
| 2 | 0.532486 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 3 | 0.532054 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.531964 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.523965 | `azmcp_eventgrid_subscription_list` | ❌ |

---

## Test 274

**Expected Tool:** `azmcp_resourcehealth_availability-status_get`  
**Prompt:** Get the availability status for resource <resource_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.643459 | `azmcp_resourcehealth_availability-status_get` | ✅ **EXPECTED** |
| 2 | 0.538239 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 3 | 0.377586 | `azmcp_quota_usage_check` | ❌ |
| 4 | 0.349997 | `azmcp_datadog_monitoredresources_list` | ❌ |
| 5 | 0.331563 | `azmcp_monitor_metrics_definitions` | ❌ |

---

## Test 275

**Expected Tool:** `azmcp_resourcehealth_availability-status_get`  
**Prompt:** Show me the health status of the storage account <storage_account_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.609642 | `azmcp_resourcehealth_availability-status_get` | ✅ **EXPECTED** |
| 2 | 0.549306 | `azmcp_storage_account_get` | ❌ |
| 3 | 0.510357 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.466881 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.455902 | `azmcp_storage_account_create` | ❌ |

---

## Test 276

**Expected Tool:** `azmcp_resourcehealth_availability-status_get`  
**Prompt:** What is the availability status of virtual machine <vm_name> in resource group <resource_group_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.638408 | `azmcp_resourcehealth_availability-status_get` | ✅ **EXPECTED** |
| 2 | 0.577415 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 3 | 0.424939 | `azmcp_mysql_server_list` | ❌ |
| 4 | 0.393482 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |
| 5 | 0.386598 | `azmcp_quota_usage_check` | ❌ |

---

## Test 277

**Expected Tool:** `azmcp_resourcehealth_availability-status_list`  
**Prompt:** List availability status for all resources in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.737234 | `azmcp_resourcehealth_availability-status_list` | ✅ **EXPECTED** |
| 2 | 0.592647 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.548549 | `azmcp_grafana_list` | ❌ |
| 4 | 0.544505 | `azmcp_subscription_list` | ❌ |
| 5 | 0.540477 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 278

**Expected Tool:** `azmcp_resourcehealth_availability-status_list`  
**Prompt:** Show me the health status of all my Azure resources  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.645009 | `azmcp_resourcehealth_availability-status_list` | ✅ **EXPECTED** |
| 2 | 0.609494 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.509740 | `azmcp_resourcehealth_service-health-events_list` | ❌ |
| 4 | 0.508252 | `azmcp_quota_usage_check` | ❌ |
| 5 | 0.473834 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 279

**Expected Tool:** `azmcp_resourcehealth_availability-status_list`  
**Prompt:** What resources in resource group <resource_group_name> have health issues?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.612392 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 2 | 0.596968 | `azmcp_resourcehealth_availability-status_list` | ✅ **EXPECTED** |
| 3 | 0.496640 | `azmcp_resourcehealth_service-health-events_list` | ❌ |
| 4 | 0.441956 | `azmcp_applens_resource_diagnose` | ❌ |
| 5 | 0.427536 | `azmcp_datadog_monitoredresources_list` | ❌ |

---

## Test 280

**Expected Tool:** `azmcp_resourcehealth_service-health-events_list`  
**Prompt:** List all service health events in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.690719 | `azmcp_resourcehealth_service-health-events_list` | ✅ **EXPECTED** |
| 2 | 0.554895 | `azmcp_search_service_list` | ❌ |
| 3 | 0.534250 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.529916 | `azmcp_eventgrid_subscription_list` | ❌ |
| 5 | 0.518399 | `azmcp_resourcehealth_availability-status_list` | ❌ |

---

## Test 281

**Expected Tool:** `azmcp_resourcehealth_service-health-events_list`  
**Prompt:** Show me Azure service health events for subscription <subscription_id>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.686448 | `azmcp_resourcehealth_service-health-events_list` | ✅ **EXPECTED** |
| 2 | 0.534704 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.513815 | `azmcp_search_service_list` | ❌ |
| 4 | 0.513259 | `azmcp_eventgrid_topic_list` | ❌ |
| 5 | 0.501135 | `azmcp_subscription_list` | ❌ |

---

## Test 282

**Expected Tool:** `azmcp_resourcehealth_service-health-events_list`  
**Prompt:** What service issues have occurred in the last 30 days?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.450841 | `azmcp_resourcehealth_service-health-events_list` | ✅ **EXPECTED** |
| 2 | 0.275820 | `azmcp_resourcehealth_availability-status_get` | ❌ |
| 3 | 0.267672 | `azmcp_applens_resource_diagnose` | ❌ |
| 4 | 0.245720 | `azmcp_cloudarchitect_design` | ❌ |
| 5 | 0.216830 | `azmcp_resourcehealth_availability-status_list` | ❌ |

---

## Test 283

**Expected Tool:** `azmcp_resourcehealth_service-health-events_list`  
**Prompt:** List active service health events in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.685391 | `azmcp_resourcehealth_service-health-events_list` | ✅ **EXPECTED** |
| 2 | 0.528118 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.524063 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.520197 | `azmcp_search_service_list` | ❌ |
| 5 | 0.502086 | `azmcp_resourcehealth_availability-status_list` | ❌ |

---

## Test 284

**Expected Tool:** `azmcp_resourcehealth_service-health-events_list`  
**Prompt:** Show me planned maintenance events for my Azure services  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.565851 | `azmcp_resourcehealth_service-health-events_list` | ✅ **EXPECTED** |
| 2 | 0.437868 | `azmcp_search_service_list` | ❌ |
| 3 | 0.403742 | `azmcp_eventgrid_subscription_list` | ❌ |
| 4 | 0.402503 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.402232 | `azmcp_foundry_agents_list` | ❌ |

---

## Test 285

**Expected Tool:** `azmcp_servicebus_queue_details`  
**Prompt:** Show me the details of service bus <service_bus_name> queue <queue_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.642876 | `azmcp_servicebus_queue_details` | ✅ **EXPECTED** |
| 2 | 0.460932 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 3 | 0.436980 | `azmcp_servicebus_topic_details` | ❌ |
| 4 | 0.375382 | `azmcp_aks_cluster_get` | ❌ |
| 5 | 0.360754 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 286

**Expected Tool:** `azmcp_servicebus_topic_details`  
**Prompt:** Show me the details of service bus <service_bus_name> topic <topic_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.642952 | `azmcp_servicebus_topic_details` | ✅ **EXPECTED** |
| 2 | 0.571861 | `azmcp_servicebus_topic_subscription_details` | ❌ |
| 3 | 0.483976 | `azmcp_servicebus_queue_details` | ❌ |
| 4 | 0.482958 | `azmcp_eventgrid_topic_list` | ❌ |
| 5 | 0.458772 | `azmcp_eventgrid_subscription_list` | ❌ |

---

## Test 287

**Expected Tool:** `azmcp_servicebus_topic_subscription_details`  
**Prompt:** Show me the details of service bus <service_bus_name> subscription <subscription_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.633187 | `azmcp_servicebus_topic_subscription_details` | ✅ **EXPECTED** |
| 2 | 0.517623 | `azmcp_servicebus_topic_details` | ❌ |
| 3 | 0.494515 | `azmcp_servicebus_queue_details` | ❌ |
| 4 | 0.493853 | `azmcp_eventgrid_topic_list` | ❌ |
| 5 | 0.472222 | `azmcp_eventgrid_subscription_list` | ❌ |

---

## Test 288

**Expected Tool:** `azmcp_sql_db_create`  
**Prompt:** Create a new SQL database named <database_name> in server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.516780 | `azmcp_sql_db_create` | ✅ **EXPECTED** |
| 2 | 0.470892 | `azmcp_sql_server_create` | ❌ |
| 3 | 0.420504 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.408515 | `azmcp_sql_db_delete` | ❌ |
| 5 | 0.404860 | `azmcp_sql_server_delete` | ❌ |

---

## Test 289

**Expected Tool:** `azmcp_sql_db_create`  
**Prompt:** Create a SQL database <database_name> with Basic tier in server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.571760 | `azmcp_sql_db_create` | ✅ **EXPECTED** |
| 2 | 0.459672 | `azmcp_sql_server_create` | ❌ |
| 3 | 0.437526 | `azmcp_sql_server_delete` | ❌ |
| 4 | 0.423999 | `azmcp_appservice_database_add` | ❌ |
| 5 | 0.420843 | `azmcp_sql_db_show` | ❌ |

---

## Test 290

**Expected Tool:** `azmcp_sql_db_create`  
**Prompt:** Create a new database called <database_name> on SQL server <server_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.604472 | `azmcp_sql_db_create` | ✅ **EXPECTED** |
| 2 | 0.545906 | `azmcp_sql_server_create` | ❌ |
| 3 | 0.504013 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.494377 | `azmcp_sql_db_show` | ❌ |
| 5 | 0.473974 | `azmcp_sql_db_list` | ❌ |

---

## Test 291

**Expected Tool:** `azmcp_sql_db_delete`  
**Prompt:** Delete the SQL database <database_name> from server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.568196 | `azmcp_sql_db_delete` | ✅ **EXPECTED** |
| 2 | 0.567412 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.391509 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.386564 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 5 | 0.364776 | `azmcp_sql_db_show` | ❌ |

---

## Test 292

**Expected Tool:** `azmcp_sql_db_delete`  
**Prompt:** Remove database <database_name> from SQL server <server_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.567513 | `azmcp_sql_server_delete` | ❌ |
| 2 | 0.543440 | `azmcp_sql_db_delete` | ✅ **EXPECTED** |
| 3 | 0.500756 | `azmcp_sql_db_show` | ❌ |
| 4 | 0.481083 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.478779 | `azmcp_sql_db_list` | ❌ |

---

## Test 293

**Expected Tool:** `azmcp_sql_db_delete`  
**Prompt:** Delete the database called <database_name> on server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.509916 | `azmcp_sql_db_delete` | ✅ **EXPECTED** |
| 2 | 0.490892 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.364494 | `azmcp_postgres_database_list` | ❌ |
| 4 | 0.355416 | `azmcp_mysql_database_list` | ❌ |
| 5 | 0.347837 | `azmcp_sql_db_rename` | ❌ |

---

## Test 294

**Expected Tool:** `azmcp_sql_db_list`  
**Prompt:** List all databases in the Azure SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.643238 | `azmcp_sql_db_list` | ✅ **EXPECTED** |
| 2 | 0.639694 | `azmcp_mysql_database_list` | ❌ |
| 3 | 0.609178 | `azmcp_postgres_database_list` | ❌ |
| 4 | 0.602890 | `azmcp_cosmos_database_list` | ❌ |
| 5 | 0.570106 | `azmcp_kusto_database_list` | ❌ |

---

## Test 295

**Expected Tool:** `azmcp_sql_db_list`  
**Prompt:** Show me all the databases configuration details in the Azure SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.617746 | `azmcp_sql_server_show` | ❌ |
| 2 | 0.609389 | `azmcp_sql_db_list` | ✅ **EXPECTED** |
| 3 | 0.557353 | `azmcp_mysql_database_list` | ❌ |
| 4 | 0.553488 | `azmcp_mysql_server_config_get` | ❌ |
| 5 | 0.524274 | `azmcp_sql_db_show` | ❌ |

---

## Test 296

**Expected Tool:** `azmcp_sql_db_rename`  
**Prompt:** Rename the SQL database <database_name> on server <server_name> to <new_database_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.593348 | `azmcp_sql_db_rename` | ✅ **EXPECTED** |
| 2 | 0.425282 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.416207 | `azmcp_sql_db_delete` | ❌ |
| 4 | 0.396947 | `azmcp_sql_db_create` | ❌ |
| 5 | 0.346018 | `azmcp_sql_db_show` | ❌ |

---

## Test 297

**Expected Tool:** `azmcp_sql_db_rename`  
**Prompt:** Rename my Azure SQL database <database_name> to <new_database_name> on server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.711063 | `azmcp_sql_db_rename` | ✅ **EXPECTED** |
| 2 | 0.516485 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.506499 | `azmcp_sql_db_delete` | ❌ |
| 4 | 0.501476 | `azmcp_sql_db_create` | ❌ |
| 5 | 0.433897 | `azmcp_sql_server_show` | ❌ |

---

## Test 298

**Expected Tool:** `azmcp_sql_db_show`  
**Prompt:** Get the configuration details for the SQL database <database_name> on server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.610995 | `azmcp_sql_server_show` | ❌ |
| 2 | 0.593096 | `azmcp_postgres_server_config_get` | ❌ |
| 3 | 0.530393 | `azmcp_mysql_server_config_get` | ❌ |
| 4 | 0.528145 | `azmcp_sql_db_show` | ✅ **EXPECTED** |
| 5 | 0.465795 | `azmcp_sql_db_list` | ❌ |

---

## Test 299

**Expected Tool:** `azmcp_sql_db_show`  
**Prompt:** Show me the details of SQL database <database_name> in server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.530095 | `azmcp_sql_db_show` | ✅ **EXPECTED** |
| 2 | 0.503681 | `azmcp_sql_server_show` | ❌ |
| 3 | 0.440073 | `azmcp_sql_db_list` | ❌ |
| 4 | 0.439057 | `azmcp_mysql_table_schema_get` | ❌ |
| 5 | 0.432919 | `azmcp_mysql_database_list` | ❌ |

---

## Test 300

**Expected Tool:** `azmcp_sql_db_update`  
**Prompt:** Update the performance tier of SQL database <database_name> on server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.603366 | `azmcp_sql_db_update` | ✅ **EXPECTED** |
| 2 | 0.467571 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.440493 | `azmcp_sql_db_rename` | ❌ |
| 4 | 0.427621 | `azmcp_sql_db_show` | ❌ |
| 5 | 0.413941 | `azmcp_sql_server_delete` | ❌ |

---

## Test 301

**Expected Tool:** `azmcp_sql_db_update`  
**Prompt:** Scale SQL database <database_name> on server <server_name> to use <sku_name> SKU  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.550556 | `azmcp_sql_db_update` | ✅ **EXPECTED** |
| 2 | 0.418358 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.401771 | `azmcp_sql_db_list` | ❌ |
| 4 | 0.395518 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.394770 | `azmcp_sql_db_show` | ❌ |

---

## Test 302

**Expected Tool:** `azmcp_sql_elastic-pool_list`  
**Prompt:** List all elastic pools in SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.678138 | `azmcp_sql_elastic-pool_list` | ✅ **EXPECTED** |
| 2 | 0.502389 | `azmcp_sql_db_list` | ❌ |
| 3 | 0.498367 | `azmcp_mysql_database_list` | ❌ |
| 4 | 0.479044 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.475405 | `azmcp_kusto_cluster_list` | ❌ |

---

## Test 303

**Expected Tool:** `azmcp_sql_elastic-pool_list`  
**Prompt:** Show me the elastic pools configured for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.606425 | `azmcp_sql_elastic-pool_list` | ✅ **EXPECTED** |
| 2 | 0.502877 | `azmcp_sql_server_show` | ❌ |
| 3 | 0.457193 | `azmcp_sql_db_list` | ❌ |
| 4 | 0.438522 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.432816 | `azmcp_mysql_database_list` | ❌ |

---

## Test 304

**Expected Tool:** `azmcp_sql_elastic-pool_list`  
**Prompt:** What elastic pools are available in my SQL server <server_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.592752 | `azmcp_sql_elastic-pool_list` | ✅ **EXPECTED** |
| 2 | 0.420325 | `azmcp_mysql_database_list` | ❌ |
| 3 | 0.402616 | `azmcp_mysql_server_list` | ❌ |
| 4 | 0.397657 | `azmcp_sql_db_list` | ❌ |
| 5 | 0.397640 | `azmcp_sql_server_show` | ❌ |

---

## Test 305

**Expected Tool:** `azmcp_sql_server_create`  
**Prompt:** Create a new Azure SQL server named <server_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.682606 | `azmcp_sql_server_create` | ✅ **EXPECTED** |
| 2 | 0.563708 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.529434 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.482102 | `azmcp_storage_account_create` | ❌ |
| 5 | 0.474207 | `azmcp_sql_db_rename` | ❌ |

---

## Test 306

**Expected Tool:** `azmcp_sql_server_create`  
**Prompt:** Create an Azure SQL server with name <server_name> in location <location> with admin user <admin_user>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.618597 | `azmcp_sql_server_create` | ✅ **EXPECTED** |
| 2 | 0.510431 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.472854 | `azmcp_sql_server_show` | ❌ |
| 4 | 0.441370 | `azmcp_sql_server_delete` | ❌ |
| 5 | 0.401244 | `azmcp_sql_db_rename` | ❌ |

---

## Test 307

**Expected Tool:** `azmcp_sql_server_create`  
**Prompt:** Set up a new SQL server called <server_name> in my resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.589818 | `azmcp_sql_server_create` | ✅ **EXPECTED** |
| 2 | 0.501403 | `azmcp_sql_db_create` | ❌ |
| 3 | 0.498314 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.461181 | `azmcp_sql_db_rename` | ❌ |
| 5 | 0.442934 | `azmcp_mysql_server_list` | ❌ |

---

## Test 308

**Expected Tool:** `azmcp_sql_server_delete`  
**Prompt:** Delete the Azure SQL server <server_name> from resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.656593 | `azmcp_sql_server_delete` | ✅ **EXPECTED** |
| 2 | 0.548064 | `azmcp_sql_db_delete` | ❌ |
| 3 | 0.518234 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.495550 | `azmcp_sql_server_create` | ❌ |
| 5 | 0.483132 | `azmcp_workbooks_delete` | ❌ |

---

## Test 309

**Expected Tool:** `azmcp_sql_server_delete`  
**Prompt:** Remove the SQL server <server_name> from my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.615073 | `azmcp_sql_server_delete` | ✅ **EXPECTED** |
| 2 | 0.393885 | `azmcp_postgres_server_list` | ❌ |
| 3 | 0.379760 | `azmcp_sql_db_delete` | ❌ |
| 4 | 0.376660 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.350203 | `azmcp_sql_server_list` | ❌ |

---

## Test 310

**Expected Tool:** `azmcp_sql_server_delete`  
**Prompt:** Delete SQL server <server_name> permanently  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.624310 | `azmcp_sql_server_delete` | ✅ **EXPECTED** |
| 2 | 0.454892 | `azmcp_sql_db_delete` | ❌ |
| 3 | 0.362389 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.341503 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.315820 | `azmcp_workbooks_delete` | ❌ |

---

## Test 311

**Expected Tool:** `azmcp_sql_server_entra-admin_list`  
**Prompt:** List Microsoft Entra ID administrators for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.783479 | `azmcp_sql_server_entra-admin_list` | ✅ **EXPECTED** |
| 2 | 0.456051 | `azmcp_sql_server_show` | ❌ |
| 3 | 0.434821 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.401908 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 5 | 0.376108 | `azmcp_sql_db_list` | ❌ |

---

## Test 312

**Expected Tool:** `azmcp_sql_server_entra-admin_list`  
**Prompt:** Show me the Entra ID administrators configured for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.713306 | `azmcp_sql_server_entra-admin_list` | ✅ **EXPECTED** |
| 2 | 0.413144 | `azmcp_sql_server_show` | ❌ |
| 3 | 0.368036 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.316036 | `azmcp_sql_db_list` | ❌ |
| 5 | 0.311085 | `azmcp_postgres_server_list` | ❌ |

---

## Test 313

**Expected Tool:** `azmcp_sql_server_entra-admin_list`  
**Prompt:** What Microsoft Entra ID administrators are set up for my SQL server <server_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.646419 | `azmcp_sql_server_entra-admin_list` | ✅ **EXPECTED** |
| 2 | 0.356025 | `azmcp_sql_server_show` | ❌ |
| 3 | 0.322402 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.307823 | `azmcp_sql_server_create` | ❌ |
| 5 | 0.269788 | `azmcp_sql_server_delete` | ❌ |

---

## Test 314

**Expected Tool:** `azmcp_sql_server_firewall-rule_create`  
**Prompt:** Create a firewall rule for my Azure SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.635466 | `azmcp_sql_server_firewall-rule_create` | ✅ **EXPECTED** |
| 2 | 0.532712 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 3 | 0.522184 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.448822 | `azmcp_sql_server_create` | ❌ |
| 5 | 0.440845 | `azmcp_sql_server_delete` | ❌ |

---

## Test 315

**Expected Tool:** `azmcp_sql_server_firewall-rule_create`  
**Prompt:** Add a firewall rule to allow access from IP range <start_ip> to <end_ip> for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.670189 | `azmcp_sql_server_firewall-rule_create` | ✅ **EXPECTED** |
| 2 | 0.533562 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 3 | 0.503648 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.316631 | `azmcp_sql_server_list` | ❌ |
| 5 | 0.302362 | `azmcp_sql_server_delete` | ❌ |

---

## Test 316

**Expected Tool:** `azmcp_sql_server_firewall-rule_create`  
**Prompt:** Create a new firewall rule named <rule_name> for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.685107 | `azmcp_sql_server_firewall-rule_create` | ✅ **EXPECTED** |
| 2 | 0.574336 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 3 | 0.539577 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.428919 | `azmcp_sql_server_create` | ❌ |
| 5 | 0.395165 | `azmcp_sql_db_create` | ❌ |

---

## Test 317

**Expected Tool:** `azmcp_sql_server_firewall-rule_delete`  
**Prompt:** Delete a firewall rule from my Azure SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.691421 | `azmcp_sql_server_firewall-rule_delete` | ✅ **EXPECTED** |
| 2 | 0.584379 | `azmcp_sql_server_delete` | ❌ |
| 3 | 0.543857 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 4 | 0.540333 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 5 | 0.498444 | `azmcp_sql_db_delete` | ❌ |

---

## Test 318

**Expected Tool:** `azmcp_sql_server_firewall-rule_delete`  
**Prompt:** Remove the firewall rule <rule_name> from SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.670140 | `azmcp_sql_server_firewall-rule_delete` | ✅ **EXPECTED** |
| 2 | 0.574405 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 3 | 0.530470 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 4 | 0.488387 | `azmcp_sql_server_delete` | ❌ |
| 5 | 0.360347 | `azmcp_sql_db_delete` | ❌ |

---

## Test 319

**Expected Tool:** `azmcp_sql_server_firewall-rule_delete`  
**Prompt:** Delete firewall rule <rule_name> for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.671212 | `azmcp_sql_server_firewall-rule_delete` | ✅ **EXPECTED** |
| 2 | 0.601230 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 3 | 0.577330 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 4 | 0.499272 | `azmcp_sql_server_delete` | ❌ |
| 5 | 0.378585 | `azmcp_sql_db_delete` | ❌ |

---

## Test 320

**Expected Tool:** `azmcp_sql_server_firewall-rule_list`  
**Prompt:** List all firewall rules for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.729372 | `azmcp_sql_server_firewall-rule_list` | ✅ **EXPECTED** |
| 2 | 0.549667 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 3 | 0.513114 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.468812 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.418702 | `azmcp_sql_server_list` | ❌ |

---

## Test 321

**Expected Tool:** `azmcp_sql_server_firewall-rule_list`  
**Prompt:** Show me the firewall rules for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.630731 | `azmcp_sql_server_firewall-rule_list` | ✅ **EXPECTED** |
| 2 | 0.524126 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 3 | 0.476757 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.410680 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.348060 | `azmcp_sql_server_list` | ❌ |

---

## Test 322

**Expected Tool:** `azmcp_sql_server_firewall-rule_list`  
**Prompt:** What firewall rules are configured for my SQL server <server_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.630546 | `azmcp_sql_server_firewall-rule_list` | ✅ **EXPECTED** |
| 2 | 0.532454 | `azmcp_sql_server_firewall-rule_create` | ❌ |
| 3 | 0.473501 | `azmcp_sql_server_firewall-rule_delete` | ❌ |
| 4 | 0.412957 | `azmcp_sql_server_show` | ❌ |
| 5 | 0.350437 | `azmcp_sql_server_list` | ❌ |

---

## Test 323

**Expected Tool:** `azmcp_sql_server_list`  
**Prompt:** List all Azure SQL servers in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.694359 | `azmcp_sql_server_list` | ✅ **EXPECTED** |
| 2 | 0.596686 | `azmcp_mysql_server_list` | ❌ |
| 3 | 0.578310 | `azmcp_sql_db_list` | ❌ |
| 4 | 0.515702 | `azmcp_sql_elastic-pool_list` | ❌ |
| 5 | 0.509789 | `azmcp_sql_db_show` | ❌ |

---

## Test 324

**Expected Tool:** `azmcp_sql_server_list`  
**Prompt:** Show me every SQL server available in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.618240 | `azmcp_sql_server_list` | ✅ **EXPECTED** |
| 2 | 0.593837 | `azmcp_mysql_server_list` | ❌ |
| 3 | 0.542445 | `azmcp_sql_db_list` | ❌ |
| 4 | 0.507425 | `azmcp_resourcehealth_availability-status_list` | ❌ |
| 5 | 0.496200 | `azmcp_group_list` | ❌ |

---

## Test 325

**Expected Tool:** `azmcp_sql_server_show`  
**Prompt:** Show me the details of Azure SQL server <server_name> in resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.629672 | `azmcp_sql_db_show` | ❌ |
| 2 | 0.595184 | `azmcp_sql_server_show` | ✅ **EXPECTED** |
| 3 | 0.587863 | `azmcp_sql_server_list` | ❌ |
| 4 | 0.559893 | `azmcp_mysql_server_list` | ❌ |
| 5 | 0.540243 | `azmcp_sql_db_list` | ❌ |

---

## Test 326

**Expected Tool:** `azmcp_sql_server_show`  
**Prompt:** Get the configuration details for SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.658817 | `azmcp_sql_server_show` | ✅ **EXPECTED** |
| 2 | 0.610507 | `azmcp_postgres_server_config_get` | ❌ |
| 3 | 0.538034 | `azmcp_mysql_server_config_get` | ❌ |
| 4 | 0.471541 | `azmcp_sql_db_show` | ❌ |
| 5 | 0.445500 | `azmcp_postgres_server_param_get` | ❌ |

---

## Test 327

**Expected Tool:** `azmcp_sql_server_show`  
**Prompt:** Display the properties of SQL server <server_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.563143 | `azmcp_sql_server_show` | ✅ **EXPECTED** |
| 2 | 0.392532 | `azmcp_postgres_server_config_get` | ❌ |
| 3 | 0.380047 | `azmcp_postgres_server_param_get` | ❌ |
| 4 | 0.372194 | `azmcp_sql_server_firewall-rule_list` | ❌ |
| 5 | 0.370539 | `azmcp_sql_db_show` | ❌ |

---

## Test 328

**Expected Tool:** `azmcp_storage_account_create`  
**Prompt:** Create a new storage account called testaccount123 in East US region  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.533552 | `azmcp_storage_account_create` | ✅ **EXPECTED** |
| 2 | 0.418472 | `azmcp_storage_account_get` | ❌ |
| 3 | 0.394541 | `azmcp_storage_blob_container_create` | ❌ |
| 4 | 0.374006 | `azmcp_loadtesting_test_create` | ❌ |
| 5 | 0.355096 | `azmcp_loadtesting_testresource_create` | ❌ |

---

## Test 329

**Expected Tool:** `azmcp_storage_account_create`  
**Prompt:** Create a storage account with premium performance and LRS replication  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.500638 | `azmcp_storage_account_create` | ✅ **EXPECTED** |
| 2 | 0.400151 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 3 | 0.387071 | `azmcp_storage_account_get` | ❌ |
| 4 | 0.382644 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |
| 5 | 0.377221 | `azmcp_sql_db_create` | ❌ |

---

## Test 330

**Expected Tool:** `azmcp_storage_account_create`  
**Prompt:** Create a new storage account with Data Lake Storage Gen2 enabled  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.589003 | `azmcp_storage_account_create` | ✅ **EXPECTED** |
| 2 | 0.464611 | `azmcp_storage_blob_container_create` | ❌ |
| 3 | 0.447156 | `azmcp_sql_db_create` | ❌ |
| 4 | 0.437040 | `azmcp_storage_account_get` | ❌ |
| 5 | 0.407411 | `azmcp_storage_blob_container_get` | ❌ |

---

## Test 331

**Expected Tool:** `azmcp_storage_account_get`  
**Prompt:** Show me the details for my storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.655152 | `azmcp_storage_account_get` | ✅ **EXPECTED** |
| 2 | 0.603853 | `azmcp_storage_blob_container_get` | ❌ |
| 3 | 0.507638 | `azmcp_storage_blob_get` | ❌ |
| 4 | 0.483435 | `azmcp_storage_account_create` | ❌ |
| 5 | 0.443365 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 332

**Expected Tool:** `azmcp_storage_account_get`  
**Prompt:** Get details about the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.676876 | `azmcp_storage_account_get` | ✅ **EXPECTED** |
| 2 | 0.612889 | `azmcp_storage_blob_container_get` | ❌ |
| 3 | 0.518215 | `azmcp_storage_account_create` | ❌ |
| 4 | 0.515153 | `azmcp_storage_blob_get` | ❌ |
| 5 | 0.464285 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 333

**Expected Tool:** `azmcp_storage_account_get`  
**Prompt:** List all storage accounts in my subscription including their location and SKU  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.664087 | `azmcp_storage_account_get` | ✅ **EXPECTED** |
| 2 | 0.557016 | `azmcp_azuremanagedlustre_filesystem_sku_get` | ❌ |
| 3 | 0.547647 | `azmcp_subscription_list` | ❌ |
| 4 | 0.536950 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.535616 | `azmcp_storage_account_create` | ❌ |

---

## Test 334

**Expected Tool:** `azmcp_storage_account_get`  
**Prompt:** Show me my storage accounts with whether hierarchical namespace (HNS) is enabled  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.499302 | `azmcp_storage_account_get` | ✅ **EXPECTED** |
| 2 | 0.461256 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |
| 3 | 0.455449 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.421645 | `azmcp_cosmos_account_list` | ❌ |
| 5 | 0.415397 | `azmcp_resourcehealth_availability-status_get` | ❌ |

---

## Test 335

**Expected Tool:** `azmcp_storage_account_get`  
**Prompt:** Show me the storage accounts in my subscription and include HTTPS-only and public blob access settings  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.557142 | `azmcp_storage_account_get` | ✅ **EXPECTED** |
| 2 | 0.473655 | `azmcp_cosmos_account_list` | ❌ |
| 3 | 0.465571 | `azmcp_subscription_list` | ❌ |
| 4 | 0.461641 | `azmcp_storage_blob_container_get` | ❌ |
| 5 | 0.436170 | `azmcp_search_service_list` | ❌ |

---

## Test 336

**Expected Tool:** `azmcp_storage_blob_container_create`  
**Prompt:** Create the storage container mycontainer in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.563396 | `azmcp_storage_blob_container_create` | ✅ **EXPECTED** |
| 2 | 0.524779 | `azmcp_storage_account_create` | ❌ |
| 3 | 0.508053 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.447784 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.403407 | `azmcp_storage_account_get` | ❌ |

---

## Test 337

**Expected Tool:** `azmcp_storage_blob_container_create`  
**Prompt:** Create the container using blob public access in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.512578 | `azmcp_storage_blob_container_create` | ✅ **EXPECTED** |
| 2 | 0.500624 | `azmcp_storage_account_create` | ❌ |
| 3 | 0.470927 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.415378 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.414820 | `azmcp_storage_blob_get` | ❌ |

---

## Test 338

**Expected Tool:** `azmcp_storage_blob_container_create`  
**Prompt:** Create a new blob container named documents with container public access in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.463198 | `azmcp_storage_account_create` | ❌ |
| 2 | 0.455375 | `azmcp_storage_blob_container_get` | ❌ |
| 3 | 0.451690 | `azmcp_storage_blob_container_create` | ✅ **EXPECTED** |
| 4 | 0.435099 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.407657 | `azmcp_cosmos_database_container_item_query` | ❌ |

---

## Test 339

**Expected Tool:** `azmcp_storage_blob_container_get`  
**Prompt:** Show me the properties of the storage container <container> in the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.665176 | `azmcp_storage_blob_container_get` | ✅ **EXPECTED** |
| 2 | 0.559177 | `azmcp_storage_account_get` | ❌ |
| 3 | 0.523288 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.518763 | `azmcp_storage_blob_get` | ❌ |
| 5 | 0.496184 | `azmcp_storage_blob_container_create` | ❌ |

---

## Test 340

**Expected Tool:** `azmcp_storage_blob_container_get`  
**Prompt:** List all blob containers in the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.613933 | `azmcp_cosmos_database_container_list` | ❌ |
| 2 | 0.605437 | `azmcp_storage_blob_container_get` | ✅ **EXPECTED** |
| 3 | 0.521995 | `azmcp_storage_blob_get` | ❌ |
| 4 | 0.481153 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.479014 | `azmcp_storage_account_get` | ❌ |

---

## Test 341

**Expected Tool:** `azmcp_storage_blob_container_get`  
**Prompt:** Show me the containers in the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.625166 | `azmcp_storage_blob_container_get` | ✅ **EXPECTED** |
| 2 | 0.592373 | `azmcp_cosmos_database_container_list` | ❌ |
| 3 | 0.511261 | `azmcp_storage_account_get` | ❌ |
| 4 | 0.479580 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.439698 | `azmcp_storage_account_create` | ❌ |

---

## Test 342

**Expected Tool:** `azmcp_storage_blob_get`  
**Prompt:** Show me the properties for blob <blob> in container <container> in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.613096 | `azmcp_storage_blob_get` | ✅ **EXPECTED** |
| 2 | 0.586223 | `azmcp_storage_blob_container_get` | ❌ |
| 3 | 0.483502 | `azmcp_storage_account_get` | ❌ |
| 4 | 0.477864 | `azmcp_cosmos_database_container_list` | ❌ |
| 5 | 0.442610 | `azmcp_cosmos_database_container_item_query` | ❌ |

---

## Test 343

**Expected Tool:** `azmcp_storage_blob_get`  
**Prompt:** Get the details about blob <blob> in the container <container> in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.662106 | `azmcp_storage_blob_container_get` | ❌ |
| 2 | 0.661919 | `azmcp_storage_blob_get` | ✅ **EXPECTED** |
| 3 | 0.537535 | `azmcp_storage_account_get` | ❌ |
| 4 | 0.460657 | `azmcp_storage_blob_container_create` | ❌ |
| 5 | 0.457038 | `azmcp_storage_account_create` | ❌ |

---

## Test 344

**Expected Tool:** `azmcp_storage_blob_get`  
**Prompt:** List all blobs in the blob container <container> in the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.592723 | `azmcp_storage_blob_container_get` | ❌ |
| 2 | 0.579070 | `azmcp_cosmos_database_container_list` | ❌ |
| 3 | 0.568421 | `azmcp_storage_blob_get` | ✅ **EXPECTED** |
| 4 | 0.506639 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.465942 | `azmcp_storage_account_get` | ❌ |

---

## Test 345

**Expected Tool:** `azmcp_storage_blob_get`  
**Prompt:** Show me the blobs in the blob container <container> in the storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.570353 | `azmcp_storage_blob_container_get` | ❌ |
| 2 | 0.549442 | `azmcp_storage_blob_get` | ✅ **EXPECTED** |
| 3 | 0.533515 | `azmcp_cosmos_database_container_list` | ❌ |
| 4 | 0.483885 | `azmcp_cosmos_database_container_item_query` | ❌ |
| 5 | 0.449128 | `azmcp_storage_account_get` | ❌ |

---

## Test 346

**Expected Tool:** `azmcp_storage_blob_upload`  
**Prompt:** Upload file <local-file-path> to storage blob <blob> in container <container> in storage account <account>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.566287 | `azmcp_storage_blob_upload` | ✅ **EXPECTED** |
| 2 | 0.403451 | `azmcp_storage_blob_get` | ❌ |
| 3 | 0.397722 | `azmcp_storage_blob_container_get` | ❌ |
| 4 | 0.382123 | `azmcp_storage_account_create` | ❌ |
| 5 | 0.377255 | `azmcp_storage_blob_container_create` | ❌ |

---

## Test 347

**Expected Tool:** `azmcp_subscription_list`  
**Prompt:** List all subscriptions for my account  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.654071 | `azmcp_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.512977 | `azmcp_cosmos_account_list` | ❌ |
| 3 | 0.471653 | `azmcp_postgres_server_list` | ❌ |
| 4 | 0.469023 | `azmcp_kusto_cluster_list` | ❌ |
| 5 | 0.457940 | `azmcp_eventgrid_subscription_list` | ❌ |

---

## Test 348

**Expected Tool:** `azmcp_subscription_list`  
**Prompt:** Show me my subscriptions  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.458821 | `azmcp_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.407465 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.393695 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.381238 | `azmcp_postgres_server_list` | ❌ |
| 5 | 0.363835 | `azmcp_redis_list` | ❌ |

---

## Test 349

**Expected Tool:** `azmcp_subscription_list`  
**Prompt:** What is my current subscription?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.433196 | `azmcp_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.315547 | `azmcp_marketplace_product_get` | ❌ |
| 3 | 0.293818 | `azmcp_eventgrid_subscription_list` | ❌ |
| 4 | 0.289334 | `azmcp_eventgrid_topic_list` | ❌ |
| 5 | 0.288229 | `azmcp_redis_list` | ❌ |

---

## Test 350

**Expected Tool:** `azmcp_subscription_list`  
**Prompt:** What subscriptions do I have?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.477592 | `azmcp_subscription_list` | ✅ **EXPECTED** |
| 2 | 0.357658 | `azmcp_eventgrid_subscription_list` | ❌ |
| 3 | 0.340837 | `azmcp_eventgrid_topic_list` | ❌ |
| 4 | 0.340339 | `azmcp_grafana_list` | ❌ |
| 5 | 0.336798 | `azmcp_postgres_server_list` | ❌ |

---

## Test 351

**Expected Tool:** `azmcp_azureterraformbestpractices_get`  
**Prompt:** Fetch the Azure Terraform best practices  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.686886 | `azmcp_azureterraformbestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.625270 | `azmcp_deploy_iac_rules_get` | ❌ |
| 3 | 0.605047 | `azmcp_get_bestpractices_get` | ❌ |
| 4 | 0.482936 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.466199 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 352

**Expected Tool:** `azmcp_azureterraformbestpractices_get`  
**Prompt:** Show me the Azure Terraform best practices and generate code sample to get a secret from Azure Key Vault  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.581316 | `azmcp_azureterraformbestpractices_get` | ✅ **EXPECTED** |
| 2 | 0.512141 | `azmcp_get_bestpractices_get` | ❌ |
| 3 | 0.510004 | `azmcp_deploy_iac_rules_get` | ❌ |
| 4 | 0.473596 | `azmcp_keyvault_secret_get` | ❌ |
| 5 | 0.444297 | `azmcp_deploy_pipeline_guidance_get` | ❌ |

---

## Test 353

**Expected Tool:** `azmcp_virtualdesktop_hostpool_list`  
**Prompt:** List all host pools in my subscription  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.711929 | `azmcp_virtualdesktop_hostpool_list` | ✅ **EXPECTED** |
| 2 | 0.659763 | `azmcp_virtualdesktop_hostpool_sessionhost_list` | ❌ |
| 3 | 0.620666 | `azmcp_kusto_cluster_list` | ❌ |
| 4 | 0.548888 | `azmcp_search_service_list` | ❌ |
| 5 | 0.535739 | `azmcp_virtualdesktop_hostpool_sessionhost_usersession-list` | ❌ |

---

## Test 354

**Expected Tool:** `azmcp_virtualdesktop_hostpool_sessionhost_list`  
**Prompt:** List all session hosts in host pool <hostpool_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.727054 | `azmcp_virtualdesktop_hostpool_sessionhost_list` | ✅ **EXPECTED** |
| 2 | 0.714469 | `azmcp_virtualdesktop_hostpool_sessionhost_usersession-list` | ❌ |
| 3 | 0.573394 | `azmcp_virtualdesktop_hostpool_list` | ❌ |
| 4 | 0.439611 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.402909 | `azmcp_aks_nodepool_get` | ❌ |

---

## Test 355

**Expected Tool:** `azmcp_virtualdesktop_hostpool_sessionhost_usersession-list`  
**Prompt:** List all user sessions on session host <sessionhost_name> in host pool <hostpool_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.812659 | `azmcp_virtualdesktop_hostpool_sessionhost_usersession-list` | ✅ **EXPECTED** |
| 2 | 0.659212 | `azmcp_virtualdesktop_hostpool_sessionhost_list` | ❌ |
| 3 | 0.501132 | `azmcp_virtualdesktop_hostpool_list` | ❌ |
| 4 | 0.356479 | `azmcp_aks_nodepool_list` | ❌ |
| 5 | 0.336415 | `azmcp_monitor_workspace_list` | ❌ |

---

## Test 356

**Expected Tool:** `azmcp_workbooks_create`  
**Prompt:** Create a new workbook named <workbook_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.552366 | `azmcp_workbooks_create` | ✅ **EXPECTED** |
| 2 | 0.433079 | `azmcp_workbooks_update` | ❌ |
| 3 | 0.361364 | `azmcp_workbooks_delete` | ❌ |
| 4 | 0.361273 | `azmcp_workbooks_show` | ❌ |
| 5 | 0.328113 | `azmcp_workbooks_list` | ❌ |

---

## Test 357

**Expected Tool:** `azmcp_workbooks_delete`  
**Prompt:** Delete the workbook with resource ID <workbook_resource_id>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.621310 | `azmcp_workbooks_delete` | ✅ **EXPECTED** |
| 2 | 0.518706 | `azmcp_workbooks_show` | ❌ |
| 3 | 0.432453 | `azmcp_workbooks_create` | ❌ |
| 4 | 0.425569 | `azmcp_workbooks_list` | ❌ |
| 5 | 0.390318 | `azmcp_workbooks_update` | ❌ |

---

## Test 358

**Expected Tool:** `azmcp_workbooks_list`  
**Prompt:** List all workbooks in my resource group <resource_group_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.772431 | `azmcp_workbooks_list` | ✅ **EXPECTED** |
| 2 | 0.563085 | `azmcp_workbooks_create` | ❌ |
| 3 | 0.532603 | `azmcp_workbooks_show` | ❌ |
| 4 | 0.516739 | `azmcp_grafana_list` | ❌ |
| 5 | 0.488600 | `azmcp_group_list` | ❌ |

---

## Test 359

**Expected Tool:** `azmcp_workbooks_list`  
**Prompt:** What workbooks do I have in resource group <resource_group_name>?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.708612 | `azmcp_workbooks_list` | ✅ **EXPECTED** |
| 2 | 0.570791 | `azmcp_workbooks_create` | ❌ |
| 3 | 0.539999 | `azmcp_workbooks_show` | ❌ |
| 4 | 0.485504 | `azmcp_workbooks_delete` | ❌ |
| 5 | 0.472378 | `azmcp_grafana_list` | ❌ |

---

## Test 360

**Expected Tool:** `azmcp_workbooks_show`  
**Prompt:** Get information about the workbook with resource ID <workbook_resource_id>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.697474 | `azmcp_workbooks_show` | ✅ **EXPECTED** |
| 2 | 0.498789 | `azmcp_workbooks_create` | ❌ |
| 3 | 0.494708 | `azmcp_workbooks_list` | ❌ |
| 4 | 0.452348 | `azmcp_workbooks_delete` | ❌ |
| 5 | 0.419054 | `azmcp_workbooks_update` | ❌ |

---

## Test 361

**Expected Tool:** `azmcp_workbooks_show`  
**Prompt:** Show me the workbook with display name <workbook_display_name>  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.469435 | `azmcp_workbooks_show` | ✅ **EXPECTED** |
| 2 | 0.455515 | `azmcp_workbooks_create` | ❌ |
| 3 | 0.437305 | `azmcp_workbooks_update` | ❌ |
| 4 | 0.424338 | `azmcp_workbooks_list` | ❌ |
| 5 | 0.366057 | `azmcp_workbooks_delete` | ❌ |

---

## Test 362

**Expected Tool:** `azmcp_workbooks_update`  
**Prompt:** Update the workbook <workbook_resource_id> with a new text step  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.469797 | `azmcp_workbooks_update` | ✅ **EXPECTED** |
| 2 | 0.382852 | `azmcp_workbooks_create` | ❌ |
| 3 | 0.362429 | `azmcp_workbooks_show` | ❌ |
| 4 | 0.349689 | `azmcp_workbooks_delete` | ❌ |
| 5 | 0.276727 | `azmcp_loadtesting_testrun_update` | ❌ |

---

## Test 363

**Expected Tool:** `azmcp_bicepschema_get`  
**Prompt:** How can I use Bicep to create an Azure OpenAI service?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.485970 | `azmcp_foundry_models_deploy` | ❌ |
| 2 | 0.485889 | `azmcp_deploy_iac_rules_get` | ❌ |
| 3 | 0.448373 | `azmcp_get_bestpractices_get` | ❌ |
| 4 | 0.440302 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.432773 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 364

**Expected Tool:** `azmcp_cloudarchitect_design`  
**Prompt:** Please help me design an architecture for a large-scale file upload, storage, and retrieval service  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.502125 | `azmcp_cloudarchitect_design` | ✅ **EXPECTED** |
| 2 | 0.290902 | `azmcp_storage_blob_upload` | ❌ |
| 3 | 0.254991 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 4 | 0.221349 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 5 | 0.217339 | `azmcp_azuremanagedlustre_filesystem_list` | ❌ |

---

## Test 365

**Expected Tool:** `azmcp_cloudarchitect_design`  
**Prompt:** Help me create a cloud service that will serve as ATM for users  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.405148 | `azmcp_cloudarchitect_design` | ✅ **EXPECTED** |
| 2 | 0.267683 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 3 | 0.258160 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 4 | 0.225870 | `azmcp_foundry_models_deploy` | ❌ |
| 5 | 0.225622 | `azmcp_deploy_plan_get` | ❌ |

---

## Test 366

**Expected Tool:** `azmcp_cloudarchitect_design`  
**Prompt:** I want to design a cloud app for ordering groceries  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.423577 | `azmcp_cloudarchitect_design` | ✅ **EXPECTED** |
| 2 | 0.271943 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 3 | 0.265972 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 4 | 0.242581 | `azmcp_deploy_plan_get` | ❌ |
| 5 | 0.218064 | `azmcp_deploy_iac_rules_get` | ❌ |

---

## Test 367

**Expected Tool:** `azmcp_cloudarchitect_design`  
**Prompt:** How can I design a cloud service in Azure that will store and present videos for users?  

### Results

| Rank | Score | Tool | Status |
|------|-------|------|--------|
| 1 | 0.534690 | `azmcp_cloudarchitect_design` | ✅ **EXPECTED** |
| 2 | 0.369969 | `azmcp_deploy_pipeline_guidance_get` | ❌ |
| 3 | 0.352797 | `azmcp_deploy_architecture_diagram_generate` | ❌ |
| 4 | 0.323920 | `azmcp_storage_blob_upload` | ❌ |
| 5 | 0.323688 | `azmcp_resourcehealth_service-health-events_list` | ❌ |

---

## Summary

**Total Prompts Tested:** 367  
**Analysis Execution Time:** 46.9787261s  

### Success Rate Metrics

**Top Choice Success:** 92.1% (338/367 tests)  

#### Confidence Level Distribution

**💪 Very High Confidence (≥0.8):** 3.5% (13/367 tests)  
**🎯 High Confidence (≥0.7):** 18.5% (68/367 tests)  
**✅ Good Confidence (≥0.6):** 61.0% (224/367 tests)  
**👍 Fair Confidence (≥0.5):** 91.6% (336/367 tests)  
**👌 Acceptable Confidence (≥0.4):** 100.0% (367/367 tests)  
**❌ Low Confidence (<0.4):** 0.0% (0/367 tests)  

#### Top Choice + Confidence Combinations

**💪 Top Choice + Very High Confidence (≥0.8):** 3.5% (13/367 tests)  
**🎯 Top Choice + High Confidence (≥0.7):** 18.5% (68/367 tests)  
**✅ Top Choice + Good Confidence (≥0.6):** 59.7% (219/367 tests)  
**👍 Top Choice + Fair Confidence (≥0.5):** 85.8% (315/367 tests)  
**👌 Top Choice + Acceptable Confidence (≥0.4):** 92.1% (338/367 tests)  

### Success Rate Analysis

🟢 **Excellent** - The tool selection system is performing very well.

⚠️ **Recommendation:** Tool descriptions need improvement to better match user intent (targets: ≥0.6 good, ≥0.7 high).

