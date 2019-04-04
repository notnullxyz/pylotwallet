# pylotWallet

A transaction aggregator and reporting tool for Eve Online pilots.

### Disclaimer

This is not going to be ready soon. It has no warranties. It is still in development. It is broken


## Get Rolling

Activate the venv and install requirements:

```shell
source venv/bin/activate
pip install -r requirements.txt
```

Export FLASK_APP env var:

```shell
export FLASK_APP=app.py
```

Make sure config is prepared, then:

```shell
flask db upgrade
```

Run the app:

```shell
python app.py
```

## References

- https://kyria.github.io/EsiPy/advanced_uses/using_own_cache/
- https://docs.esi.evetech.net/
- https://esi.evetech.net/ui/?datasource=tranquility#/Wallet/get_characters_character_id_wallet

## Author
Marlon van der Linde <marlonv@protonmail.com>

Using EsiPy and Flask
