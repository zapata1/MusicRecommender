# Music Recommandation

docker build : 
	$: docker build -t recommender .
1. Lancer le container avec le volume ou sont stockées les datas
	$: docker run -v /path/to/my/data/:/docker/path/data/ -it recommendercluster

2. Récupérer son id
	$: docker container ls

3. Exécuter le recomendador avec l'userId
	$: docker exec -it _id_ spark-submit recommendador_2.11-0.1.0.jar 1000002

