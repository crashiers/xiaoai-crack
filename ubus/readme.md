## list

+  ai_crontab
+  alarm
+  dlna
+  led
+  mediaplayer
+  messagingagent
+  mibrain
+  mibt
+  miio
+  network
+  network.device
+  network.interface
+  network.interface.lan
+  network.interface.loopback
+  network.wireless
+  nightmode
+  notify
+  pnshelper
+  qplayer
+  service
+  system
+  upnp-disc
+  voip
+  volctl
+  wifitool
+  workday


### args


#### ai_crontab
'ai_crontab' @c85e9773
	"new":{"personal_skill":"String"}
	"notify":{"src":"String","event":"String","id":"String"}
	"remove_all":{}
	"dump":{"busy":"Integer","free":"Integer"}
#### alarm
'alarm' @1dedfb7b
	"mibrain_operation":{"mibrain":"String"}
	"alarm_create":{"type":"String","timestamp":"Integer","circle":"Integer","volume":"Integer","event":"String","extra":"String","behavior":"String","ringtone_query":"String","ringtone_type":"String","display_txt":"String","time_reminder":"String"}
	"alarm_query":{"type":"String"}
	"alarm_delete":{"type":"String","id":"String"}
	"alarm_close":{"type":"String","id":"String"}
	"alarm_open":{"type":"String","id":"String"}
	"alarm_modify":{"type":"String","id":"String","timestamp":"Integer","circle":"Integer","volume":"Integer","event":"String","extra":"String","behavior":"String","ringtone_query":"String","ringtone_type":"String","display_txt":"String","time_reminder":"String"}
	"create":{"type":"String","timestamp":"Integer","circle":"Integer","volume":"Integer","event":"String","extra":"String","behavior":"String","ringtone_query":"String","ringtone_type":"String","display_txt":"String","time_reminder":"String"}
	"query":{"type":"String"}
	"delete":{"type":"String","id":"String"}
	"close":{"type":"String","id":"String"}
	"open":{"type":"String","id":"String"}
	"modify":{"type":"String","id":"String","timestamp":"Integer","circle":"Integer","volume":"Integer","event":"String","extra":"String","behavior":"String","ringtone_query":"String","ringtone_type":"String","display_txt":"String","time_reminder":"String"}
	"micmute":{"hour":"Integer","minute":"Integer","second":"Integer"}
	"micmute_remove":{}
#### dlna
'dlna' @4ce6e9ae
	"demo":{"mac":"String","action":"String"}
	"play":{"mac":"String","action":"String"}
	"status":{"mac":"String","action":"String"}
#### led
'led' @78abec6a
	"show":{"L":"Integer","pos":"Integer","rgb":"String"}
	"shut":{"L":"Integer"}
	"status":{}
	"shut_all":{}
#### mediaplayer
'mediaplayer' @749c928c
	"player_wakeup":{"action":"String","source":"String"}
	"player_play_operation":{"media":"String","action":"String"}
	"player_play_url":{"url":"String","type":"Integer","domain":"String","media":"String","src":"String","id":"String","duration":"Integer"}
	"player_get_play_status":{}
	"player_play_status":{}
	"player_play_private_fm":{}
	"player_get_latest_playlist":{}
	"player_set_positon":{"position":"Integer","media":"String"}
	"player_set_loop":{"type":"Integer","media":"String"}
	"player_play_music":{"music":"String","startOffset":"Integer","loadMoreOffset":"Integer","media":"String","src":"String","id":"String","duration":"Integer"}
	"player_set_volume":{"volume":"Integer","media":"String"}
	"player_set_continuous_volume":{"volume":"Integer","media":"String"}
	"player_modify_volume":{"isVolumeUp":"Integer","value":"Integer"}
	"player_get_context":{}
	"player_play_index":{"index":"Integer","media":"String"}
	"player_play_alarm_reminder":{"type":"Integer","reminder":"String","volume":"Integer","timeReminder":"String","query":"String"}
	"player_play_album_playlist":{"type":"Integer","id":"String","startOffset":"Integer","media":"String"}
	"media_control":{"player":"String","action":"String","volume":"Integer"}
	"player_set_shutdown_timer":{"action":"String","hour":"Integer","minute":"Integer","second":"Integer","media":"String"}
	"test":{}
	"get_shutdown_timer":{}
	"get_media_volume":{}
	"player_reset":{}
	"player_retore_last_volume":{}
	"set_voip_status":{"voip_status":"String"}
	"set_player_quiet":{"quiet":"Boolean"}
	"set_playrate":{"rate":"String"}
	"notify_mdplay_status":{"status":"Integer","type":"Integer"}
	"player_aux_operation":{"aux_operation":"String"}
#### messagingagent
'messagingagent' @bd5bbd4f
	"notify":{"payload":"String"}
	"identify_device":{}
	"miot_push":{"payload":"String"}
	"report_events":{"payload":"String"}
	"add_device_log":{"mac":"String","payload":"String"}
	"set_kv":{"key":"String","value":"String"}
	"close":{}
	"get_pid":{}
	"fault":{}
	"sync_admin":{}
	"get_ai_service_token":{}
#### mibrain
'mibrain' @9d7d7caa
	"nlp_result_get":{}
	"text_to_speech":{"text":"String","caller":"String","vendor":"String","codec":"String","volume":"Integer","save":"Integer","play":"Integer"}
	"vendor_switch":{"vendor_name":"String"}
	"vendor_who":{}
	"ai_service":{"bypass":"String","caller":"String","duration":"Integer","id":"String","asr":"Integer","nlp":"Integer","tts":"Integer","asr_audio":"String","nlp_text":"String","nlp_execute":"Integer","tts_text":"String","tts_type":"String","tts_vendor":"String","tts_volume":"Integer","tts_codec":"String","tts_save":"Integer","tts_play":"Integer"}
	"aivs_miio_token_update":{"token":"String","session_id":"String"}
	"aivs_authorization_get":{}
	"aivs_event_post":{"namespace":"String","name":"String","payload":"String"}
	"aivs_track_post":{"event":"String","dialog_id":"String","extend":"String"}
	"aivs_env_switch":{}
	"tts_vendor_switch":{"vendor_name":"String"}
	"tts_vendor_show":{}
#### mibt
'mibt' @da0813b2
	"wakeup_tv":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"connect":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"connect_and_play":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"lock":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"status":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"unpair":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"ble":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"enable":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"disconnect":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"volume":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"volume_action":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"play":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"switch_role":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"scan_bt":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"get_scan_bt":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"display_conn":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
	"debug":{"mac":"String","name":"String","recent":"String","action":"String","btmode":"String","volume":"Integer","connect":"Integer","discover":"Integer","btrole":"String"}
#### miio
'miio' @efe16487
	"renew":{}
	"register":{"ssid":"String","psk":"String","uid":"String","country":"String"}
	"drop":{}
	"token_write":{"token":"String","session_id":"String","ttl":"String"}
	"miio_restore_status":{}
#### network
'network' @51d67f39
	"restart":{}
	"reload":{}
	"add_host_route":{"target":"String","v6":"Boolean","interface":"String"}
	"get_proto_handlers":{}
	"add_dynamic":{"name":"String"}
#### network.device
'network.device' @6c48ce6a
	"status":{"name":"String"}
	"set_alias":{"alias":"Array","device":"String"}
	"set_state":{"name":"String","defer":"Boolean"}
#### network.interface
'network.interface' @824adad3
	"up":{}
	"down":{}
	"status":{}
	"prepare":{}
	"dump":{}
	"add_device":{"name":"String","link-ext":"Boolean"}
	"remove_device":{"name":"String","link-ext":"Boolean"}
	"notify_proto":{}
	"remove":{}
	"set_data":{}
#### network.interface.lan
'network.interface.lan' @6e4e9b86
	"up":{}
	"down":{}
	"status":{}
	"prepare":{}
	"dump":{}
	"add_device":{"name":"String","link-ext":"Boolean"}
	"remove_device":{"name":"String","link-ext":"Boolean"}
	"notify_proto":{}
	"remove":{}
	"set_data":{}
#### network.interface.loopback
'network.interface.loopback' @30102251
	"up":{}
	"down":{}
	"status":{}
	"prepare":{}
	"dump":{}
	"add_device":{"name":"String","link-ext":"Boolean"}
	"remove_device":{"name":"String","link-ext":"Boolean"}
	"notify_proto":{}
	"remove":{}
	"set_data":{}
#### network.wireless
'network.wireless' @01c2f7ee
	"up":{}
	"down":{}
	"status":{}
	"notify":{}
	"get_validate":{}
#### nightmode
'nightmode' @1cb6eb2d
	"set":{"total":"String","light":"String","volume":"String","start":"String","stop":"String"}
	"status":{}
	"current":{}
#### notify
'notify' @10d3873e
	"create":{"id":"String","level":"Integer","expire":"Integer","volume":"Integer","text":"String"}
	"query":{"id":"String"}
	"delete":{"id":"String"}
	"play":{}
	"stop":{}
	"clean":{}
	"status":{"level":"Integer"}
	"set":{"level":"Integer","enable":"Integer","autoplay":"Integer","volume":"Integer"}
#### pnshelper
'pnshelper' @e56be10e
	"event_notify":{"src":"Integer","event":"Integer","detail":"String"}
#### qplayer
'qplayer' @41f40184
	"play":{"play":"String","light":"Integer"}
#### service
'service' @ee67d7e0
	"set":{"name":"String","script":"String","instances":"Table","triggers":"Array","validate":"Array","autostart":"Boolean"}
	"add":{"name":"String","script":"String","instances":"Table","triggers":"Array","validate":"Array","autostart":"Boolean"}
	"list":{"name":"String","verbose":"Boolean"}
	"delete":{"name":"String","instance":"String"}
	"signal":{"name":"String","instance":"String","signal":"Integer"}
	"update_start":{"name":"String"}
	"update_complete":{"name":"String"}
	"event":{"type":"String","data":"Table"}
	"validate":{"package":"String","type":"String","service":"String"}
	"get_data":{"name":"String","instance":"String","type":"String"}
	"state":{"spawn":"Boolean","name":"String"}
#### system
'system' @5a550b2d
	"board":{}
	"info":{}
	"reboot":{}
	"watchdog":{"frequency":"Integer","timeout":"Integer","magicclose":"Boolean","stop":"Boolean"}
	"signal":{"pid":"Integer","signum":"Integer"}
	"sysupgrade":{"path":"String","prefix":"String","command":"String"}
#### upnp-disc
'upnp-disc' @9d4924e5
	"demo":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
	"lookup":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
	"select":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
	"wakeup":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
	"list":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
	"enable":{"mac":"String","udn":"String","select":"Integer","enable":"Integer"}
#### voip
'voip' @bb41b65d
	"voip_signal_op":{"op":"Integer","uid":"String"}
	"action":{"vender":"String","event":"String","contact_id":"String","number":"String","name":"String","string":"String"}
	"cmcc_register":{"msisdn":"String","type":"String","operation":"Integer"}
	"cmcc_unregister":{"msisdn":"String","type":"String","operation":"Integer"}
	"cmcc_miscellaneous":{"msisdn":"String","type":"String","operation":"Integer"}
#### volctl
'volctl' @5015c14d
	"setvol":{"callername":"String","softnode":"String","vol":"Integer"}
	"setvolfine":{"callername":"String","softnode":"String","vol":"Integer"}
	"getvol":{"callername":"String","softnode":"String"}
	"volup":{"callername":"String","softnode":"String"}
	"voldown":{"callername":"String","softnode":"String"}
	"volrel":{"callername":"String","softnode":"String","vol":"Integer"}
	"vollinerel":{"callername":"String","softnode":"String","vol":"Integer"}
	"volline":{"callername":"String","softnode":"String","vol":"Integer"}
	"nightmode":{"callername":"String","val":"Integer"}
#### wifitool
'wifitool' @1ce770e0
	"getrssi":{"get_rssi":"String"}
	"setswitch":{"set_switch":"String"}
	"pushrssi":{"push_rssi":"Integer"}
	"getbssid":{"get_bssid":"String"}
#### workday
'workday' @62cfc3c6
	"get_config":{"name":"String"}
	"get_version":{}
	"get_ts":{}
	"sync_config":{"force":"Boolean","check_ts":"Boolean"}


