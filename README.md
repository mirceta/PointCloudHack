# PointCloudHack

### MILESTONE 1

- Point cloud of Slovenia from Satelite data VUCKO
	- Get data from API for Slovenia
	- Save data to .txt format:
		- x y z R G B
		- 0.0 0.0 0.0 255 122 122

- Label 5 locations with spheres -> clickable VUCKO 
	- ```5 spheres```
	- ```respond to click event```
- When click:
	- Unload satellite point cloud
		- ```Unload point cloud```
		- ```Load another point cloud```
		- ```Fade to black + loading screen + spawn at starting point```
	- Load 1sqkm region in Slovenia
		- ```use PointCloud plugin```
- Add surrounding region Satellite data
	- ```Concatenate 2 point clouds```

### MILESTONE 2
- Game mechanics
	- ```Actor that moves through the scene```
	- ```Can shoot```
	- ```Shoots AI agents```
- Multi-player VUCKO