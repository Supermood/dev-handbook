# Role

<< [Concept](/concept.md)

## Mooder

This role is assigned to people who work at supermood.

### Technical condition

To be modder it is necessary to have in the table `users` the values ​​in the following fields:

```json
{
    "userType": "App\Admin",
    "companyId": "<supermood_company_id>"
}
```

> In development, we have the possibility to change the ID of the supermood company, for this it is necessary to add in the file `supermood/platform/backend/services/supermood-api/.env` the variable `SUPERMOOD_COMPANY_ID=<companyID>`.

