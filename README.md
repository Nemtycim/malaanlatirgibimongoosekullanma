# malaanlatirgibimongoosekullanma
Bende MongoDB(mongoose)'De yeniyim küfür etmeyin yanlısım varsa yardımım dokunduysa star atin

# 1. Mongoose İşlemimiz
-> Bot çalısınca mongo ya baglanma
= Main dosyanıza şunu yazın
![image](https://user-images.githubusercontent.com/101521169/177275686-1be17209-b3f5-41f6-968d-77c8b546381a.png)

# 2. Mongoose İşlemimiz
-> Şema tanımlama 
= Schema diye dosya(klasör) açın ve dosyanın(klosör) içine <istediğinad>.js dosyası açın

![image](https://user-images.githubusercontent.com/101521169/177276144-e719a2f8-3ee0-4b5e-9c1b-e7eb3580838c.png)

# 3. Mongoose İşlemimiz
-> Schema doldurma = gerekli şeyleri doldurcaz (resimdeki gibi yapabilirsiniz)

![image](https://user-images.githubusercontent.com/101521169/177276475-fb421c95-f4f6-4ab8-b40d-0b39d371c4de.png)

# 4. Mongoose İşlememiz
-> Mongoose'de veri ekleme veri pushlama veri silme(bunu biliyom ama biraz)

`>` **Veri Ekleme** 

`await <doyalıyolutanımı>.findOneAndUpdate({ guildID: message.guild.id, userID: message.author.id }, { $inc: { <verin1>: 1,<verin2>: 1, }, }, { upsert: true });`

`>` **Veri Pushlama**

`await <doyalıyolutanımı>.findOne({ guildID: message.guild.id, userID: member.id });
${data ? data.<verin> : 0}`


# Son Olarak
-> Mongo.db(Mongoose) kullanmayın akıl sağlığınız bozulur.
