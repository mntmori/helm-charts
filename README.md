# helm-charts

0. helm repo add [repository name] https://mntmori.github.io/helm-charts/charts/

1. helm package [chart name]

2. Copy package to my-repo/charts

3. Upload chart to repository 

cd /charts

wget https://mntmori.github.io/helm-charts/charts/index.yaml

helm repo index --merge index.yaml --url https://mntmori.github.io/helm-charts/charts/ ./

4. 

git add . 
git commit -m 'added chart'
git push

helm search repo -l
