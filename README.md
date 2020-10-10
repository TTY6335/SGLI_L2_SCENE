# SGLI_L2_SCENE
HDF5 to Geotiff converter for GCOM-C/SGLI OCEAN PRODUCTS

GCOM-C/SGLI L2 の海洋プロダクトのHDF5のファイルをgeotiffに変換するプログラムです。 
L2の海洋プロダクトはL1と同じくシーン単位で作成されるため[こちら](https://github.com/TTY6335/SGLI_L2) では使えません。  
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
