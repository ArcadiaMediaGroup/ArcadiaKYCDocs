## Welcome to the Arcadia KYC Documentation

Arcadia Media Group's Optical Character Recognition based KYC, AML and PEP system, Arcadia KYC is a closed API service offered at [https://ArcadiaKYC.com](https://ArcadiaKYC.com)
### Getting An API Key

Administratiors and Sales Reps can provide API keys upon request via [email](mailto:info@arcadiamgroup.com) or via the form on site.

### Checking Identification Via API

Currently the Arcadia KYC  upload  REST  API  URL  is built out at 

https://ArcadiaKYC.com/api/submitOrdersubmit  

Current Identification API Parameters
POST  /api/submitOrder  
HTTP/1.1  
Host: ArcadiaKYC.com
Content-Type:  multipart/form-data Content-Disposition:  form-data;
name="public_key": PUBLICKEYHERE Content-Disposition:  form-data;
name="private_key"  PRIVATEKEYHERE Content-Disposition:  form-data;
name="order_type"  National Content-Disposition:  form-data;
name="country_id"  840 Content-Disposition:  form-data;
name="original_id"  11111111 Content-Disposition:  form-data;
name="name"  HAPPY Content-Disposition:  form-data;
name="surname"  TRAVELER  Content-Disposition:  form-data;
name="placebirth"  WASHINGTON  Content-Disposition:  form-data;
name="birthday"  2018-07-05Content-Disposition:  form-data;
name="expire"  07  AUG  2016  Content-Disposition:  form-data;
name="serial"  340007237Content-Disposition:  form-data; 
name="document_photo";  filename="PASSPORTIMAGE.png" Content-Type:  image/png 
