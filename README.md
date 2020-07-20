# CloudedBats - on the web

This is a part of CloudedBats: http://cloudedbats.org

**Note: This repository will soon be removed and replace by a new one.**

## Installation

    git clone https://github.com/cloudedbats/cloudedbats_web_archive.git
    cd cloudedbats_web_archive
    python3 -m venv venv
    source venv/bin/activate
    pip install -r requirements.txt 
    python manage.py makemigrations
    python manage.py migrate
    python manage.py runserver

    # Web address: http://localhost:8000

The only parts working in this version are:

- A small example showing bat activity plotted with Bokeh.
- The species lists with data extracted from IUCN Redlist.

## Contact

Arnold Andreasson, Sweden.

info@cloudedbats.org
