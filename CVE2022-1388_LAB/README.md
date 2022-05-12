# CVE2022-1388_TestAPI
A Test API for testing the POC against CVE-2022-1388

To run from host.

```bash
pip install -r requirements.txt
uvicorn main:app --reload
```

To run from Docker.

```bash
make build 
make run
```

