# DIY P6/MSX Cartridge

## overview
PC-6001用の8KBカートリッジ基板です。
改造すると、MSXでも使用できます。

## files

p6_cart.comp : cartridge PCB CAD data(for 'CADLUS X').

wr.prg : 書き込み用ソフト(Raspberry Pi + Pi STARTER).

wr.py : 書き込み用ソフト(Raspberry Pi + Python)

https://github.com/nicotakuya/diyfccartridge/blob/main/wr_fc.py

## カートリッジ基板用部品
(U1) 1Mbit フラッシュメモリ SST39SF010A

(RA1) 10k ohm 4素子 集合抵抗

(LED1) LED

(R2) 4.7k ohm抵抗	 

(C1) コンデンサ	 

## ライター用部品
(U1/2) I/Oエクスパンダ MCP23S17

(U4) 48M05 低ドロップ5V三端子レギュレータ

(U3) 74HC32

(CN1) 50pinカードエッジコネクタ

(CN2) 2x20pin ピンソケット

(LED1/2/3)

(R1/2/3/4)

## movie

https://www.youtube.com/watch?v=-RcxGhLIrCQ

https://www.youtube.com/watch?v=LfQrAbjb77U

## images

![pcb_cart](https://user-images.githubusercontent.com/5597377/131228265-2837db02-c855-462e-a33b-6ee6289cb1ce.png)
