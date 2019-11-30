[global]
sonarr_server_ids = 1
radarr_server_ids = 1
lidarr_server_ids = false
tautulli_server_ids = 1
ombi_server_ids = 1
sickchill_server_ids = false
unifi_server_ids = false

[influxdb]
url = localhost
port = 8088
ssl = false
verify_ssl = false
username =
password =

[tautulli-1]
url = webhost.norum.home:8181
fallback_ip = 192.168.1.200
apikey = be334ea76cfa436b97f96e71585165c7
ssl = false
verify_ssl = false
get_activity = true
get_activity_run_seconds = 30
get_stats = true
get_stats_run_seconds = 3600

[sonarr-1]
url = sonarr.norum.home:8989
apikey = 8cb22cef67cc42a1a29e022b65dce0b7
ssl = false
verify_ssl = false
missing_days = 7
missing_days_run_seconds = 300
future_days = 1
future_days_run_seconds = 300
queue = true
queue_run_seconds = 300

[radarr-1]
url = radarr.norum.home:7878
apikey = 8708db70503e4a5cba9da07dada59de6
ssl = false
verify_ssl = false
queue = true
queue_run_seconds = 300
get_missing = true
get_missing_run_seconds = 300

[ombi-1]
url = ombi.norum.home:5000
apikey = cec42597a51e409bb3985c0e7900f07b
ssl = false
verify_ssl = false
get_request_type_counts = true
request_type_run_seconds = 300
get_request_total_counts = true
request_total_run_seconds = 300
get_issue_status_counts = true
issue_status_run_seconds = 300

[unifi-1]
url = wifiman.norum.home:8443
username = netmon
password = Gelethin
site = default
usg_name = MyRouter
ssl = true
verify_ssl = false
get_usg_stats_run_seconds = 300
