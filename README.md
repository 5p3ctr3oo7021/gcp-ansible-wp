# GCP-ANSIBLE-WP

## python venv

* python venv létrehozása: 
  ```sh
  python3 -m venv venv
  ```
*python venv aktiválása: source venv/bin/activate
  ```sh
  source venv/bin/activate
  ```

## ansible

* GCP VM példányok listázása, állapotának lekérdezése: 
  ```sh
  ansible-inventory -i inventory.gcp.yml --list
  ```
