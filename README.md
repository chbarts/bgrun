=== Run Programs In The Background ===

Run any program in the background with intelligent standard output and standard error capture.

Example:

     bgrun youtube-dl https://youtu.be/6srPCZhecOY https://youtu.be/L958sMz1kWs

This runs `youtube-dl` in the current directory and redirects all of its standard output and standard error to `youtube-dl-$(date -Iseconds)` also in the current directory.