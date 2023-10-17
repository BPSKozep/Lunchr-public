# Lunchr-public

## A Lunchr projekt publikus verziója

---

# Telepítés

### Szükséges programok:
- [Node.js](https://nodejs.org/en/)
- [Git](https://git-scm.com/)
- [MongoDB](https://www.mongodb.com/)

## Telepítés

1. `git clone https://github.com/BPSKozep/lunchr-public`
2. `cd lunchr-public`
3. `npm install`
4. `.env fájl kitöltése`
    1. `MONGODB_URI=[MongoDB connection string]`
    2. `MONGODB_DATABASE=[Adatbázis neve]`
    3. `NEXT_PUBLIC_SOCKETIO_PASSPHRASE=[Backend csatlakozáshoz jelszó]`

MongoDB-hez ajánljuk a [cloud.mongodb.com](https://cloud.mongodb.com/)-ot.

5. `npm run build`
6. `npm run start`
7. `http://localhost:3000` megnyitása böngészőben