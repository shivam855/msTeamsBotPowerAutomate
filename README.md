# msTeamsBotPowerAutomate

#GitHub Curl

  **WorkFlow Tigger** :     -- curl --location --request POST 'https://api.github.com/repos/shivam855/cypress/actions/workflows/test.yml/dispatches' \
                            --header 'Accept: application/vnd.github.everest-preview+json' \
                            --header 'Authorization: Bearer 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' \
                            --header 'Content-Type: text/plain' \
                            --header 'Cookie: _octo=GH1.1.1343356819.1666694358; logged_in=no' \
                            --data-raw '{
                              "ref": "main"
                            }'
