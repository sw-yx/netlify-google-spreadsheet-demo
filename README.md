# netlify dev + google sheets api v4 demo

check https://netlify-google-spreadsheet-demo.netlify.com/

![googlesheets](https://user-images.githubusercontent.com/6764957/74577961-ecb51800-4f5f-11ea-9b81-30a5fcb6e68c.gif)


## How to get the env vars:

- tutorial to come

## to set this up for local dev

make sure to set env vars inside `functions/google-spreadsheet-fn/.env`:

```bash
TRY_TO=CUSTOMIZE_THIS
GOOGLE_SPREADSHEET_ID_FROM_URL= # e.g. 10abcu_reo5FctMpuiOYHJstj3lTit4pvp-VS7mZhgVw
GOOGLE_SERVICE_ACCOUNT_EMAIL= # e.g. googlenetlify-spreadsheet-test@foo-bar-123456.iam.gserviceaccount.com
GOOGLE_PRIVATE_KEY= # e.g. -----BEGIN PRIVATE KEY-----\nMIIEvAIBADANBgkqhkiG etc etc super long key
```

and then with the Netlify CLI you can run `ntl dev` ([Netlify Dev](https://github.com/netlify/cli/blob/master/docs/netlify-dev.md)) and it opens up locally for you to develop.

## to set this up on your own in production on netlify

make sure to set the env vars in the netlify UI
