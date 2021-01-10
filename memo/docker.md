docker-compose up  
docker-compose run --rm web rails db:setup  
git checkout -b main origin/main(develop)  
git flow init  
git flow feature start branch_name  
git push origin branch_name

routingの記述順について  

zipメソッド  
N+1問題