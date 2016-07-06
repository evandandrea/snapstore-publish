# snapstore-publish

    $ export MACAROON_SECRET="You're not my supervisor"
    $ macaroon-create > ~/.store-upload-macaroon.enc
    $ snapstore-publish --name cassandra --series 16 --channel beta
