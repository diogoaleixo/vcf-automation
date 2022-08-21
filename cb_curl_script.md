curl 'https://cb.lab.local/v1/sddcs/validations' -i -u admin:*Flameng0 -X POST \
    -H 'Content-Type: application/json' \
    -H 'Accept: application/json' \
    -d @http-request-cb.json
