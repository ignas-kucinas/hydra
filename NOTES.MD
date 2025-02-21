
Table containing all DB tables (excluding migrations) for hydra service and number of references it has to and it is reference by other DB tables


| Table                                          | References | Referency by |
|------------------------------------------------|------------|--------------|
| hydra_client                                   | 0          | 8            |
| hydra_jwk                                      | 0          | 1            |
| **hydra_oauth2_access**                        | 2          | 0            |
| hydra_oauth2_authentication_session            | 0          | 1            |
| **hydra_oauth2_code**                          | 2          | 0            |
| **hydra_oauth2_flow**                          | 2          | 5            |
| hydra_oauth2_jti_blacklist                     | 0          | 0            |
| hydra_oauth2_logout_request                    | 1          | 0            |
| hydra_oauth2_obfuscated_authentication_session | 1          | 0            |
| hydra_oauth2_oidc                              | 2          | 0            |
| hydra_oauth2_pkce                              | 2          | 0            |
| hydra_oauth2_refresh                           | 2          | 0            |
| hydra_oauth2_trusted_jwt_bearer_issuer         | 1          | 0            |
| networks                                       | 0          | 0            |

3 Tables that are read/write on every `hydra_oauth2_flow` `hydra_oauth2_code` `hydra_oauth2_access`
