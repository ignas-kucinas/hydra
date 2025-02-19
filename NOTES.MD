
Table containing all DB tables (excluding migrations) for hydra service and number of references it has to and it is reference by other DB tables 


| Table                                          | References | Referency by |
|------------------------------------------------|------------|--------------|
| hydra_client                                   |1           |8             |
| hydra_jwk                                      |1           |1             |
| **hydra_oauth2_access**                        |3           |0             |
| hydra_oauth2_authentication_session            |1           |1             |
| **hydra_oauth2_code**                          |3           |0             |
| **hydra_oauth2_flow**                          |3           |5             |
| hydra_oauth2_jti_backlist                      |1           |0             |
| hydra_oauth2_logout_request                    |2           |0             |
| hydra_oauth2_obfuscated_authentication_session |2           |0             |
| hydra_oauth2_oidc                              |3           |0             |
| hydra_oauth2_pkce                              |3           |0             |
| hydra_oauth2_refresh                           |3           |0             |
| hydra_oauth2_trusted_jwt_bearer_issuer         |2           |0             |
| networks                                       |0           |13            |

3 Tables that are read/write on every `hydra_oauth2_flow` `hydra_oauth2_code` `hydra_oauth2_access`