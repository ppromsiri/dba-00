# Manual instructions

## สิ่งที่ต้องเตรียมก่อนลงมือปฏิบัติ
- สมัคร GitHub -> [Subscribe](https://github.com/)
- สมัคร Ngrok -> [Subscribe](https://ngrok.com/)

## ติดตั้ง hands-on environment
`bash setup.sh`

## สร้าง MongoDB สำหรับทดสอบ
`mlaunch init --replicaset`

## ทดสอบ connect MongoDB ด้วย mongosh
`mongosh "mongodb://localhost:27017,localhost:27018,localhost:27019?replicaSet=replset"`

## แหล่งอ้างอิง
- [Mtools](https://rueckstiess.github.io/mtools/index.html)
- [Setup Ngrok](https://stackoverflow.com/questions/70296667/how-do-i-connect-to-mongodb-running-in-github-codespaces-using-mongodb-compass/70636614#70636614)