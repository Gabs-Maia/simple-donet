### Catalog interface:

- USER:
    name : string
    password : string
    birth-date : date[obj]
    phone : string
    email : string
    social-media : arr[string]
    cpf : arr[nums]
    cnpj : arr[nums]
    isUserValid : bool
    role : enum[string]
    posts : collection[strings]


- CATALOG:
    prodcut : product[obj]
    genre : string
    price : int
    quantity : int
    popularity : float

- PRODUCT:
    name : string
    type : string
    purchase-value : int
    sell-value : int 
    priority : int
    times-sold : int
    distributors : arr[string]
    

- PRODUCT_INDICIES:
    user-last-purchase : string[purchase-code]
    age-purchase : int
    gender-purchase : int
    eco-class : string
    monthly-pay : int
    skin-color : string 


- META-DATA:
    materials : arr[string]
    investiment : arr[int]
    due : date[obj]

### ESPECIFIACTION: 

- ARCHITECTURE: MVC
- SYNCHRONOUS 
- NON-PARALLEL 