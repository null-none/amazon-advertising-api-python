=======
Unofficial Amazon Sponsored Products Python client library.
=======

=======
Example
=======

.. code-block:: python

    from amazon_advertising_api.advertising_api import AdvertisingApi

    CLIENT_ID = ''
    CLIENT_SECRET = ''
    ACCESS_TOKEN = ''
    REGION = 'na'

    advertising = AdvertisingApi(client_id=CLIENT_ID,
                                 client_secret=CLIENT_SECRET,
                                 region=REGION,
                                 access_token=ACCESS_TOKEN)
    print(advertising.list_campaigns())
