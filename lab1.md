####ESBII Lab 01 - AWS Windows Instance

#Introduction to Amazon Web Services(AWS)
##part 01
-------------------------------------------------------

#### 1. Create and logging to the Amazon Web Service Account ####

#### 2. Creating a Windows Server Instance ####

	2.1 Connect Using Remote Desktop
	
	2.2 Connect Using ssh secure tunnel

#### 3. Creating a Linux Server Instance ####

	3.1 Connect Using Remote Desktop
	
	3.3 Connect Using ssh secure tunnel

---------------------------------------------------------

##Screenshots

### 	1. Creating AWS Account ###




**Creating new account**
![image2](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11695725_1087420291268960_5462623056639481653_n.jpg?oh=4949322097accc09c578b640bdcdb675&oe=56151265&__gda__=1444283971_da3d83c2fa88410c0f14cf467fbfd658)

**Pin verification**
![image3](https://fbcdn-sphotos-h-a.akamaihd.net/hphotos-ak-xfp1/v/t1.0-9/10408094_1087420691268920_1715344291798419004_n.jpg?oh=e706447aec74bd88aed8966531c0a1b1&oe=564E746C&__gda__=1448519740_db1d38ddccc7370888f9006879d61bcb)



-------------------------------------------------------------
#### 	1.1 Logging to the AWS Account ####

**Services available in AWS**
![image4](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xtf1/v/t1.0-9/11742711_1087420281268961_7111938392949144760_n.jpg?oh=19d6759a3701e976aaa968cc26f09a6c&oe=5611C8A3&__gda__=1448811019_5d93f52047ccc78c43c27c0f3772bbf8)


-------------------------------------------------------------
### 	2. Creating a Windows Instance ###

**Selecting windows image**
![image5](https://fbcdn-sphotos-b-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11703149_1087420294602293_6607468632139559571_n.jpg?oh=9f7ac150e0976ba2c0ff23c808df7aea&oe=56132F6B&__gda__=1448912461_df8e424a6a522512aa20a84a3019396f)

**Since the free version only supports minimal performances no changes done to the configurations**


**Creating a key pair**
![image6](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpf1/v/t1.0-9/1610973_1087420347935621_3448175328918435304_n.jpg?oh=2624f32f3859ba1f348c80de4eb7a4d3&oe=5653F7AF)

**Running instance**
![image7](https://fbcdn-sphotos-g-a.akamaihd.net/hphotos-ak-xpf1/v/t1.0-9/11041640_1087420384602284_999994249390760942_n.jpg?oh=cd5e1ffa71148b8047e9e3bb691f5753&oe=5617B07E&__gda__=1443987732_b8a4fb7c6bdafa8ef3304a7239d0ba09)

-------------------------------------------------------------

#### 	2.1 Connect Using Remote Desktop ####

![image8](https://fbcdn-sphotos-g-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11705345_1087436877933968_1596662065622396388_n.jpg?oh=2dd0e5796dea9b5e2da4ee10a560efc3&oe=560ED73D&__gda__=1447970331_f91707152253da68ed70536eafa84912)

**Logging to the remote desktop by double click the remote desktop icon**

![image9](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xpa1/v/t1.0-9/11540948_1087436881267301_8959130057612869511_n.jpg?oh=9254f165df87cc7fe1d86651b0086e1e&oe=565B0365)




### 	3. Creating a Linux Instance ###

**Selecting Linux Image**
![image10](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xft1/v/t1.0-9/11754239_1087420787935577_3444562400648269806_n.jpg?oh=bb4f29a10076eb237fbc3761c29efcad&oe=564CCE45)

**Since the free version only supports minimal performances no changes done to the configurations**


**Creating a key pair**
![image11](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xpa1/v/t1.0-9/11223970_1087440501266939_8145224693358615233_n.jpg?oh=1898d3d4b83ba3ccdc9c43d249de155a&oe=561DA989&__gda__=1444721123_8f960f1005b6801a1882ef9dad4a15d5)
**Since there is an existing key pair**

**SSH using putty**
![image12](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xfa1/v/t1.0-9/11751843_1087420394602283_432606292685042045_n.jpg?oh=5c589cbea9a9e9ba52fdb06b933b17b7&oe=56156EDF)

**.pem file was converted to a .ppk file to be used in putty**
![image13](https://fbcdn-sphotos-f-a.akamaihd.net/hphotos-ak-xtp1/v/t1.0-9/11696016_1087420431268946_7680147476889528302_n.jpg?oh=3c413eca307eeb3f2ede192113864e34&oe=5656F054&__gda__=1443784562_b3a12c2450b07cc2147b65455169cb62)

**logging to the instance**
![image14](https://fbcdn-sphotos-d-a.akamaihd.net/hphotos-ak-xft1/v/t1.0-9/11742735_1087420451268944_4376263844371303072_n.jpg?oh=ca839428e69c81e754b10c5b26a0ea39&oe=564C2242&__gda__=1448081187_d5016bd4e3d8908228b8698806b9037d)

![image15](https://fbcdn-sphotos-b-a.akamaihd.net/hphotos-ak-xfp1/v/t1.0-9/11215810_1087420454602277_7760899850994080526_n.jpg?oh=26c460910424b2e22d04c3eb5e32161b&oe=56582B98&__gda__=1448648136_f15c76d1241c2d3ebccd03f3997b870e)

**updating the instance**
![image16](https://scontent-sin1-1.xx.fbcdn.net/hphotos-xtp1/v/t1.0-9/p206x206/11703029_1087420484602274_5830223473646225917_n.jpg?oh=58108518f1419f618351171c661e2ac1&oe=56534F82)