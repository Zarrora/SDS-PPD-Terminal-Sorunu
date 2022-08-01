### tmux kurulumu:

* y/n onayı çıkınca y diyelim.

```
apt-get install tmux
```

### oturum açalım:
```
tmux new-session -s sds
```

### SDS nodu başlatalım:

* Burayıda resim alamadım, burada en sonda ERROR yazacak ve sonunda "please register at first" yazacak, yazana kadar bekleyelim.

* Çıktıyı aldıktan sonra ctrl+b bası kısa bir süre sonra d'ye basalım, aynı anda basmayın çıkış yapmaz.

```
cd ~/rsnode
ppd start
```

### screeni yüklüyoruz:
```
apt-get install screen
```

### terminal adında screen oluşturuyoruz:
```
screen -S terminal
```

### resource node ile etkileşim kurabilmek için ek terminal açalım:

* buradan sonra komutları girerken ">" işaretlerinin üzerine yazıyoruz.

```
cd ~/rsnode
ppd terminal
```

![image](https://user-images.githubusercontent.com/101149671/181835946-cc4227ed-7b10-4875-8e2c-61f34d786616.png)
