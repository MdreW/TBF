# TBF
## Top Bike Framework
```mermaid
flowchart TD
  subgraph Top Bike Framework
    SSO-->TOUR
    SSO-->RENT
    SSO-->BLOG
    SSO-->STORE
    SSO-->PAY
    TOUR-->PAY
    RENT-->PAY
    STORE-->PAY
    TOUR-->STOREHOUSE
    RENT-->STOREHOUSE
    STORE-->STOREHOUSE
  end
```
### SSO 
**Single Sign On** for all Service. Is a proxy from others authenticarion (local, google, facebook, ecc.)

### TOUR
**TBT | Top Bike Tour** this service manage tour and experiences https://github.com/MdreW/tbt

### RENT
**TBR | Top Bike Rent** this service is a rent service

### BLOG
**TBB | Top Bike Blog** simple blog with news, probably wordpress, comments for the framework

### STORE
**TBS | Top Bike Store** Market

### PAY
**TBP | Top Bike Payment** Proxy for framework payment and order history

### STOREHOUSE
**Top Bile Storehouse** centralized for all service
