# GCP-ANSIBLE-WP

## python venv

* python venv létrehozása: 
  ```sh
  python3 -m venv venv
  ```
* python venv aktiválása:
  ```sh
  source venv/bin/activate
  ```

## ansible

* GCP VM példányok listázása, állapotának lekérdezése: 
  ```sh
  ansible-inventory -i inventory.gcp.yml --list
  ```
