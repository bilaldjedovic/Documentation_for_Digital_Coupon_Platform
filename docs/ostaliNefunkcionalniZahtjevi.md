# **5. Other non-functional requirements**

## **5.1 Performance Requirements**

The system should be able to process a large number of visits and transactions, that is, it should be enabled to
the system works under any conditions. System response and access to stored data,
that is, the integrity and authenticity of the data must not be compromised in any way.

## **5.2 Security Requirements**

N/A. There are currently no security requests.

## **5.3 Security Requirements**


| Security Requirement  | Description                                                                                                          |
|-----------------------|----------------------------------------------------------------------------------------------------------------------|
| SZ-1                  | The system should contain a subsystem for user authentication and authorization at login, using tokens.              |
| SZ-2                  | The system should grant additional capabilities only to those users who log in with valid credentials.               |
| SZ-3                  | The system should allow registered users to change their system generated username as he/she wants.                  |
| SZ-4                  | The system should block the registration of a user using an invalid email.                                           |
| SZ-5                  | The system should block the registration of a user who uses a password that does not have a minimum of 8 characters. |
| SZ-6                  | The system would allow registered users to change their password.                                                    |
| SZ-7                  | The system should prevent changing the registered user's password, if it does not contain a minimum of 8 characters. |
| SZ-8                  | The system should allow users to log in with a changed password.                                                     |
| SZ-9                  | The system should include restore and recovery features to prevent data loss.                                        |
| SZ-10                 | The system should ensure data integrity and authenticity.                                                            |

## **5.4 Software Quality Attributes**

| Software Quality Attributes   | Description                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                              |
|-------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| AKS-1                         | Simplicity - The user's technical background should not be an obstacle for understanding and using the system, i.e. the system should be easy to use. All users of the system, both visitors and registered users, should be able to use the system without training or training, i.e. intuitively. The average number of errors should not exceed three per one hour of system use.                                                                                                                                                                                                                     |
| AKS-2                         | Consistency - The list of available and active coupons should be updated and display a new coupon with exactly the data specified by the user when creating it. Also, the number of "likes" and comments displayed under a specific coupon should be sure to refer to the exact specific coupon. One way to measure data consistency is to generate a percentage of how many data points are the same across datasets and platforms. So if 80 out of 100 data points are the same wherever they appear, then the data consistency score is 80%. System consistency must be greater than or equal to 90%. |
| AKS-3                         | Reliability - The system should maintain a list of available coupons even when the system crashes. In order to make the system more reliable and to reduce the recovery time due to an error, we will use a "cloud" database.                                                                                                                                                                                                                                                                                                                                                                            |