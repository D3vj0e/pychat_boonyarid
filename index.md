## ส่งโครงการ Pychat app สามารถดาวน์โหลดเเละใช้งานได้เลย

โครงการชื่อว่า การพัฒนาแอพพลิเคชั่น Pychat App สำหรับการสื่อสารภายในองค์กร

### การใช้งานฝั่ง Server
โดยขั้นเเรกต้องตั้งค่าเรื่องของ ip ก่อนโดยเข้าไปแก้โค๊ดเเละเปลื่ยน ip เป็นเครื่องของเรา

```markdown
if __name__ == '__main__':
    server = ThreadedHTTPServer(('192.168.1.8', 8080), Serv) <- ให้ทำการเเก้ตรงนี้
    print(banner)
    print('Starting server, use <Ctrl-C> to stop')
    server.serve_forever()
```


ให้ทำการเชื่อมต่อเครือข่ายก่อนเเล้วให้ใช้คำสั่งใน terminal 
python servre.py
การตั้งค่าฝั่ง server เสร็จเเล้วก็เเก้ในส่วนของผู้ใช้งาน โดยการใส่ ip และ port ให้ตรงกับที่เราตั้งค่ากับ server

```markdown
URL = 'http://192.168.1.8:8080' <- ให้ทำการเเก้ตรงนี้
USERNAME = input("Enter you name >").encode('utf-8')
SESSION = requests.Session()
```

แล้วใช้คำสั่ง python client.py เริ่มการทำงานเเล้วใส่ชื่อผู้ใช้งานได้เลย

[file here](/D3vj0e/pychat_boonyarid/archive/refs/heads/gh-pages.zip")

# นายบุญฤทธิ์ ยังช่วย ปวส 2/4 เลขที่ 10
