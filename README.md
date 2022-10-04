# Sigma is the store's e-commerce style.

There is pagination as well as filters, allowing users to navigate and filter by specific brands or types.
Additionally, users can search for products.

In addition, there is a breadcrumb navigation bar at the top of the page, and users may simply add items to their basket.

## Serverside:
https://github.com/jahanalem/sigma-backend-dotnet

Stack Technologies: .NET 6, C#, Postgresql, Redis, and Entity Framework as an ORM

Redis is utilized to keep the customer's shopping cart in server memory. This is a memory-based data repository. Its primary function in the world is typically for caching. It operates on a key-value pair data structure and is extremely quick and persistent in memory.

Repository and Unit Of Work are implemented, as well as Generic and Specification Pattern.



## Clientside:
https://github.com/jahanalem/sigma-frontend-angular

Stack Technologies: Angular, Typescript, and Bootstrap


As a payment services provider that enables merchants to take credit cards, Stripe has been utilized.
