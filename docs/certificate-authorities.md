# Certificate Authorities

## Org-Tesla

### Create CA

Let’s begin with creating certificate authority to initiate the creation of peer org. Click on Add Certificate Authority. 

![create-ca](assets/create-ca.png)

It will show a prompt asking for two options, whether to create a new CA (or) To import CA. Select to create new CA and click on Next. 

![create-ca-promt](assets/create-ca-promt.png)

For creating new CA, you will need to fill the following inputs.  

1) Display Name – Peer Org CA display name. </br>
2) Domain – Domain to be used with peer endpoints. </br>
3) Organization Name – Name of Peer Org. </br>
4) CA Name – Name of Peer Org CA. </br>
5) Admin Identity Name – Name of Org Admin Identity. </br>
6) Admin Identity Password – Password of Org Admin Identity. </br>

Fill in and click on Next. 

![create-ca-details](assets/create-ca-details.png)

It will then verify if CA subdomain is pointed to IP or not. Click on Confirm. 

![verify-ca-subdomain](assets/verify-ca-subdomain.png)

![confirm-ca-creation](assets/confirm-ca-creation.png)

Once the CA creation is done, you will receive the success prompt like below. 

![ca-success-prompt](assets/ca-success-prompt.png)

Under the Register Identity tab in CA module, you will see the list of identities registered to the CA which includes a peer, org user and org admin. 

![registered-identities](assets/register-identity.png)


## Org-Netflix

### Create CA

Follow all steps from creating CA till adding peer to create the second peer org. 

![create-ca](assets/create-ca-2.png)

![ca-details](assets/org-netflix-ca-details.png)

![verify-netflix-subdomain](assets/verify-netflix-domain.png)

![netflix-ca-created-prompt](assets/netflix-ca-created-prompt.png)