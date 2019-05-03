# Examples of using the NGXS library
## Getting Started
* Clone the repository into a local folder.<br>
* Install dependencies `yarn install`<br>
* Run any project example `yarn start:X` where `X` is a number of the example<br>
* Try experimenting with code

## Description of examples
1. A simple NGXS store for three components. The application fetches and displays data from Wiki API. It will demonstrate handling actions as asynchronous entities and practical goals, that can be achieved with [Action Handlers](https://ngxs.gitbook.io/ngxs/advanced/action-handlers). 	Why subscribe to action immediately after its dispatching, and why subscribe to action in another component.<br><br>
*Used plugins:* [Devtools](https://ngxs.gitbook.io/ngxs/plugins/devtools)<br>
*Level:* Easy

2. How to process and display data from multiple stores/selectors with a single selector. The example features two stores. The first one stores complex entity objects (shop clients, as an example). The second store keeps the IDs of these entities. The example will demonstrate how to create a selector in the second store to display the list of client profiles, using the IDs from its list.<br><br>
*Used plugins:* [Devtools](https://ngxs.gitbook.io/ngxs/plugins/devtools)<br>
*Level:* Easy

3. Document printing using a new tab. Implements a lazy loading module and the [Storage-plugin](https://ngxs.gitbook.io/ngxs/plugins/storage) for data transfer.<br><br>
*Used plugins:* [Storage](https://ngxs.gitbook.io/ngxs/plugins/storage) + [Devtools](https://ngxs.gitbook.io/ngxs/plugins/devtools)<br>
*Level:* Medium

4. An example of an e-shop CMS will show how to combine several server requests into a single frontend state model. The example will include two caching stores for dictionaries of clients and goods, and another store with orders. It will demonstrates using a chain of actions and requests.<br><br>
*Used plugins:* [Forms](https://ngxs.gitbook.io/ngxs/plugins/form) + [Storage](https://ngxs.gitbook.io/ngxs/plugins/storage) + [Devtools](https://ngxs.gitbook.io/ngxs/plugins/devtools) + [Logger](https://ngxs.gitbook.io/ngxs/plugins/logger)<br>
*Level:* Advanced
