# AWS-EMR-LABR3-ST0263

# HDFS-s3

<img width="785" alt="image" src="https://user-images.githubusercontent.com/53051443/170848386-1242e97c-dc94-4c5d-985a-7bdd293b3f75.png">

Primeramente se hace el S3 publico para los fines de la entrega 

https://bobbyhadz.com/blog/aws-s3-allow-public-read-access

## SSH

```
ssh -i Your.pem hadoop@ec2-x-x-x-x.compute-1.amazonaws.com

```
## Crear HDFS directorio

```
hdfs dfs -mkdir /user/hadoop/datasets
```
## Subir datasets
```
sudo scp -r -i Your.pem /yourdir/datasets/ hadoop@ec2-x-x-x-x.compute-1.amazonaws.com:~/.
```
```
hdfs dfs -copyFromLocal datasets/* /user/hadoop/datasets/
```
Mirar si se copio bien
```
hdfs dfs -ls /user/hadoop/datasets/gutenberg-small/
```

# HUE 
<img width="807" alt="image" src="https://user-images.githubusercontent.com/53051443/170848686-51d97747-cd3f-41c0-9670-c8fc58ad0833.png">

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170848691-ec32af3c-0220-4d2c-b4bd-d1354e711c72.png">

<img width="960" alt="image" src="https://user-images.githubusercontent.com/53051443/170848694-277c6656-8b35-4bc5-92ae-c3dfc91903ca.png">

