# de-zoomcamp-2024
Homework, project and necessary documents for Data Engineering Zoomcamp 2024 by DataTalks.Club (DTC).

## Environment Setup (Homework)
1. Install [Docker](https://www.docker.com)
2. Install [Google Cloud SDK](https://cloud.google.com/sdk/docs/install-sdk)
3. Install [Python 3.x](https://www.python.org/)
4. Create, activate a python virtual environment, and upgrade pip.
```bash
python3 -m venv <env_name>
source <env_name>/bin/activate
pip install --upgrade pip
```
5. Install required packages.
```bash
pip install "psycopg[binary,pool]"
pip install pandas SQLAlchemy jupyter psycopg2-binary pgcli
```