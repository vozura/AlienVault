This is a plugin for IIS-10.

It will parse IIS v10 events in the following format:

#Fields: date time s-sitename s-computername s-ip cs-method cs-uri-stem cs-uri-query s-port cs-username c-ip cs-version cs(User-Agent) cs(Cookie) cs(Referer) cs-host sc-status sc-substatus sc-win32-status sc-bytes cs-bytes time-taken

Copy the tar.gz file and untar to the root directory on the AlienVault senzor. After that restart the ossim-agent and enable the plugin globally.
