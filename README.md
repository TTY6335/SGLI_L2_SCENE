# SGLI_L2_SCENE
HDF5 to Geotiff converter for GCOM-C/SGLI OCEAN PRODUCTS

# Notice  
This function merged to [SGLI_L2](https://github.com/TTY6335/SGLI_L2)  
This repository is no longer updated.
L2の投影変換を一つのプログラムでできるようにし、統合しました。  
今後は[こちら](https://github.com/TTY6335/SGLI_L2) を改良していきます。


GCOM-C/SGLI L2 の海洋プロダクトのHDF5のファイルをgeotiffに変換するプログラムです。  
~L2の海洋プロダクトはL1と同じくシーン単位で作成されるため[こちら](https://github.com/TTY6335/SGLI_L2) では使えません。~  
対象のプロダクトは

L2-正規化海水射出放射輝度 等  
- NWLR (正規化海水射出放射輝度)  
- ACP (大気補正パラメータ)  
- PAR (光合成有効放射)  

L2-クロロフィルa濃度 等  
- CHLA クロロフィルa濃度  
- TSM 懸濁物質濃度  
- CDOM　有色溶存有機物吸光係数 

L2-海面水温  
- SST 海面の（バルク）温度（雲検知含む）

# 環境  
 開発環境は以下です。
* CentOS Linux release 7.7.1908 (Core)
* python 3.7.4
* h5py 2.9.0
* hdf5 1.10.4
* numpy 1.16.5
* gdal 1.11.4
