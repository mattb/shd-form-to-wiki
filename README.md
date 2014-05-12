Google Docs form to Science Hack Day Wiki converter
---------------------------------------------------

This ruby script takes the data from a Google Docs form and publishes it to a Science Hack Day wiki page, formatted neatly.

To customise it for your Science Hack Day, you'll need to change some configuration at the top of the file:

    GOOGLE_USER="someone@gmail.com" # your Google Docs username
    GOOGLE_PASSWORD="your_password" # your Google Docs password
    GOOGLE_DOC_ID="01234567890123456789012345678901234567890123" # the ID of your copy of the Google Form copied from its URL
    PBWORKS_API_KEY="xyz" # the API key for your PBWorks setup
    PBWORKS_WIKI_PAGE="sfhacks2013" # the page on the wiki you want to publish to

The script requires ruby 1.8, and depends on the Ruby gem google-spreadsheet-ruby.
