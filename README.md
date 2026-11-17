# penpot

```bash
kubectl -n penpot exec -it deploy/penpot-backend -- \
  python3 manage.py create-profile \
  -e admin@shubhamtatvamasi.com \
  -n "Shubham Tatvamasi" \
  -p 'yourpassword'
```
