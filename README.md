# Abstract
An open dataset for typical people mass movement in urban areas

Article link(https://authors.elsevier.com/sd/article/S0968090X17302644)
+ Takehiro Kashiyama, Yanbo Pang, Yoshihide Sekimoto, Open PFLOW: Creation and evaluation of an open dataset for typical people mass movement in urban areas, Transportation Research Part C: Emerging Technologies, Volume 85, Pages 249–267, December 2017.

## Contact
If you have something to ask us about the dataset, please contact : ksym[at]iis.u-tokyo.ac.jp

[Web site: Sekimoto lab, Institute of Industrial Science, University of Tokyo](http://sekilab.iis.u-tokyo.ac.jp/staffs/)

## Citation
If you use or find out our dataset useful, please cite our paper in your paper.

# Format
+ id : unique agent id (int)
+ time : YYYY/MM/DD HH:mm:ss(char[])
+ longitude : SRID-4326(double)
+ latitude: SRID-4326(double)
+ transport: STAY-99, WALK-1, VEHICLE-2, TRAIN-3, BICYCLE-4(int)


All agents have the same magnification factor value (55.6).

# DataSet
Tokyo metropolitan area(
[file1](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory01.tsv.zip "tokyo")
,[file2](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory02.tsv.zip "tokyo")
,[file3](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory03.tsv.zip "tokyo")
,[file4](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory04.tsv.zip "tokyo")
,[file5](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory05.tsv.zip "tokyo")
,[file6](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory06.tsv.zip "tokyo")
,[file7](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory07.tsv.zip "tokyo")
,[file8](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory08.tsv.zip "tokyo")
,[file9](https://open-research-data.s3.ap-northeast-1.amazonaws.com/openpflow/trajectory09.tsv.zip "tokyo")
)

# License
Images on this dataset are available under the [Creative Commons Attribution-NonCommercial 4.0 International License](http://creativecommons.org/licenses/by-nc/4.0/) (CC BY-NC 4.0). The license and link to the legal document can be found next to every image on the service in the image information panel and contains the CC BY-NC 4.0 mark:

# Visualization
### [sample](http://shiba.iis.u-tokyo.ac.jp/member/ueyama/mm/)
Let's click 'Show Sample Data' button

### [movie1](movie/tokyo_point.mp4 "movie1")
People distribution visualized in a time series representation. Each dot represents a person.

![tokyo_point](images/tokyo_point.png "tokyo_point")

### [movie2](movie/tokyo_tail.mp4 "movie2")
Trips visualized in a time series representation. Each line represents a trip, and each color represents a movement status (green: train, orange: vehicle). 

![tokyo_tail](images/tokyo_tail.png "tokyo_tail")


