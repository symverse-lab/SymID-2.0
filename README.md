# SymID-2.0

1. Purpose of Use
Symverse blockchain is a permissioned blockchain based on a SymID, which consists of a 10-byte hexadecimal string. Therefore, all users who wish to use the Symverse blockchain must be issued a SymID. SymID is essential for issuing transactions and setting oracle parameters. However, its composition as a 10-byte hexadecimal string makes it difficult for users to remember, hindering its function as an ID. To address this issue, we support the creation of a UserID that matches SymID on a 1:1 basis, consisting of characters or numbers, to allow users to use it conveniently.

2. User ID Creation Rules
The User ID must be composed only of alphabetic characters and numbers.
The length must be between 3 and 20 characters.
The first character must be an alphabetic character.
User IDs are case-insensitive.
Duplicate User IDs are not allowed.
User IDs can be changed.
