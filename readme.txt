
/*
可以参考高德官方2014-03-11 Android SDK V2.2.0 demos中的TileOverlay的实现。
*
TileProvider tileProvider = new LocalTileProvider(Environment.getExternalStorageDirectory()+"/tile/32/");
tileOverlay = aMap.addTileOverlay(new TileOverlayOptions().tileProvider(tileProvider));