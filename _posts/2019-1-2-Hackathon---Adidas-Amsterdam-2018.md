> [Code on Git](https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018)

<img src="https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018/blob/master/adidas.JPG" width="130" height="100" />

# 01AdiCode
This project was developed by team '01AdiCode',  under 48 hrs for https://adidas-hack.com/location/Amsterdam

We are able to handcraft an amazing next generation shopping experience powered by blockchain, enabled with NFC and delivered on the mobile. The solution is intended to reveal the product journey and prove the authenticity of a product. 

### More about it...
> https://www.linkedin.com/pulse/staying-fit-adidas-hackathon-amsterdam-2018-vivek-bombatkar?trk=portfolio_article-card_title

### The team's pager
> https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018/blob/master/Team_One_Pager.pdf

### Frontend Screenshots
> https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018/blob/master/Frontend_Screenshots.pdf

### Technical solution
> https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018/blob/master/Solution%20Focus.pdf


## Get it sttarted 

### Get the code locally
```
git clone https://github.com/vivek-bombatkar/Adidas_Amsterdam_2018.git
```

### Prerequist 
 - install [Azure CLI](https://docs.microsoft.com/en-us/cli/azure/install-azure-cli?view=azure-cli-latest)
 - install [teraform docker](https://github.com/broadinstitute/docker-terraform)
 
### Deploy azure cloud insfrastruture and build sevice containers
```
./scripts/deploy-from-local.sh
```

### Folder Structure

```bash
|infrastructure : Teraform files to deploy cloud infra to Azure
|scripts : Scripts to help deployement from local machine
|api-gateway : Central point of entry for the diferent APIs (express-gateway)
|product-api : Product Rest API (PHP/Symfony/api-platform)
|product-record-api : Python code for implementation of private blockchain
|row_data
```

### Access the frontend "code" Outsystems: https://devenv.outsystemscloud.com
```
Environment: adicode-code.outsystemscloud.com
User: 01adicode@gmail.com
Pass: 01ADICODEzzz (edited)
```


