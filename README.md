# Firebase
## VS Code Firebase and Firestore snippets
-------------------
[![Version](https://vsmarketplacebadge.apphb.com/version-short/peterhdd.firebase-firestore-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=peterhdd.firebase-firestore-snippets)
[![Installs](https://vsmarketplacebadge.apphb.com/installs/peterhdd.firebase-firestore-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=peterhdd.firebase-firestore-snippets)
[![Downloads](https://vsmarketplacebadge.apphb.com/downloads-short/peterhdd.firebase-firestore-snippets.svg)](https://marketplace.visualstudio.com/items?itemName=peterhdd.firebase-firestore-snippets)

## Supported Languages
* JavaScript (.js)
* TypeScript (.ts)
* JavaScript React (.jsx)
* TypeScript React (.tsx)
* Html (.html)
* Vue (.vue)

## Snippets

### Firebase
| Trigger  | Description |
| -------: | ------ |
| `fireconfig`   | Configure Firebase |
| `firereference`   | Get a reference to the firebase service |
| `fireset`   | Set data to the firebase database |
| `fireretrieve`   | Retrieve data from firebase |
| `fireretrieveloop`   | Retrieve data and loop inside the direct children |
| `fireval`   | Using `val()` method to retrieve the data inside a listener |
| `fireretrieveonce`   | Retrieve data once |
| `firekey`   | Create a key and simultaneously retrieve the key |
| `fireupdate`   | Updating specific fields |
| `fireremove`   | Remove data at a certain location |
| `firetransaction`   | firebase transactions |
| `fireorderBychild`   | Order results by the value of a specified child key or nested child path |
| `fireorderByvalue`   | Order results by child values |
| `fireorderBykey`   | Order results by child keys |
| `firelimittofirst`   | Sets the maximum number of items to return from the end of the ordered list of results |
| `firelimittolast`   | Sets the maximum number of items to return from the beginning of the ordered list of results |
| `firestartAt`   | Return items greater than or equal to the specified key or value, depending on the order-by method chosen |
| `fireendat`   | Return items less than or equal to the specified key or value, depending on the order-by method chosen |
| `fireequalto`   | Return items equal to the specified key or value, depending on the order-by method chosen |
| `fireexists`   | Returns true if this dataSnapshot contains any data |
| `firehaschild`   | Returns true if this datasnapshot contains the specified child |
| `firehaschildren`   | Returns true is this datasnapshot contains any children |
| `firenumchildren`   | Returns the number of child properties of this datasnapshot |
| `firedetach`   | Removing a listener |
| `firestorageref`   |Get a reference to the storage service, which is used to create references in your storage bucket |
| `firestoragechildref`   | Create a reference to a location lower in the tree, say `images.jpg` |
| `firestorageurlref`   | Create a reference from a Google Cloud Storage URI or https url |
| `firestoragedownloadfile`   | Getting the download file from firebase storage |
| `firestoragedeletefile`   | Delete a file |
| `firesignupemail`   | Authenticate a new user using email and password |
| `firesigninemail`   | Sign in an existing user |
| `fireauthstate`   | Attach an observer using onAuthStateChanged to retrieve user infomration |
| `firecurrentuser`   | Retrieves the currently logged in user |
| `fireuserprofile`   | Retrieves the user information |
| `fireupdateprofile`   | Updates the user profile |
| `fireproviderinfo`   | Retrieves information from sign in provider |
| `fireupdateemail`   | Set a user email address, the user must have signed in recently|
| `fireemailverify`   | Send an email verification to the user |
| `firesetpass`   | Set a user password, the user must have signed in recently |
| `firepassreset`   | Send a password reset email to a user |
| `firedeleteuser`   | Delete a user account with the delete method |
| `firesignout`   | Sign out the user |
| `firegoogleinstance`   | Get instance of the google provider |
| `fireprovidersignin`   | Sign in with google |
| `firefacebookinstance`   | Get instance of facebook provider |
| `firetwitterinstance`   | Get instance of twitter provider |
| `firegithubinstance`   | Get instance of github provider |
| `firecustomauth`   | Sign in the user using custom authentication |
| `fireanonymously`   | Sign in the user anonymously |

### Firestore
| Trigger  | Description |
| -------: | ------- |
| `initializefirestore`   | Initialize Cloud Firestore through Firebase |
| `adddatafirestore`   | Creating a new collection and document in firestore |
| `setdatafirestore` | Creates or overwrite a single document, use the `set()` method |
| `readdatafirestore`   | Read data from a collection in firestore |
| `referencefirestore`   | Add firestore reference |
| `updatefirestore`   | Update the document in firestore |
| `deletedocfirestore`   | Delete a document in firestore |
| `deletefieldfirestore`   | Delete a field in firestore document |
| `wherefirestore`   | where query in firestore |
| `arraycontainsfirestore` | Using `array-contains` it filters based on array value |
| `limitfirestore`   | Retrieves the first three value of the field |
| `ordermultifirestore`   | Order by multiple fields in firestore |
| `realtimeupdatefirestore` | Listens for realtime changes on a document using `onSnapshot` |
|`arrayunionfieldfirestore`|	Adds an element to an array field|
`arrayremovefieldfirestore`|	Remove an element from array field|
|`incrementfieldfirestore`|	Increment or decrement a numeric field value|

