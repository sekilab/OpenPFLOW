# Abstract
An open dataset for typical people mass movement in urban areas

Article link(https://authors.elsevier.com/sd/article/S0968090X17302644)
+ Takehiro Kashiyama, Yanbo Pang, Yoshihide Sekimoto, Open PFLOW: Creation and evaluation of an open dataset for typical people mass movement in urban areas, Transportation Research Part C: Emerging Technologies, Volume 85, Pages 249–267, December 2017.

If you have something to ask us about the dataset, please contact : ksym[at]iis.u-tokyo.ac.jp

# Format
+ id : unique agent id (int)
+ time : YYYY/MM/DD HH:mm:ss(char[])
+ longitude : SRID-4326(double)
+ latitude: SRID-4326(double)
+ transport: STAY-99, WALK-1, VEHICLE-2, TRAIN-3, BICYCLE-4(int)
+ magnification factor: (double)

# DataSet
+ [tokyo metropolitan area](https://share.cw503.net/owncloud/index.php/s/u9MttDfTiAPUDsJ "tokyo")
+ chukyo metropolitan area(preparing)
+ hanshin metropolitan area(preparing)

# Visualization
### [sample](http://shiba.iis.u-tokyo.ac.jp/member/ueyama/mm/)
Let's click 'Show Sample Data' button

### [movie1](movie/tokyo_point.mp4 "movie1")
People distribution visualized in a time series representation. Each dot represents a person.

![tokyo_point](images/tokyo_point.png "tokyo_point")

### [movie2](movie/tokyo_tail.mp4 "movie2")
Trips visualized in a time series representation. Each line represents a trip, and each color represents a movement status (green: train, orange: vehicle). 

![tokyo_tail](images/tokyo_tail.png "tokyo_tail")
