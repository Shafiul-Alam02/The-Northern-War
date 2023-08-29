# The-Northern-War

The Brotherhood of Sorcerers is the oldest organization of mages in the Northern Realm. Mages are skilled and educated in the usage of magic. Magic academies like Aretuza, Ban Ard and Rissberg are united and controlled by the Brotherhood. Mages are trained to harness the power of Chaos in these magic academies or schools. After the training, mages are sent to various courts in the realm. They work as advisors to the king of those kingdoms. Aedrin, Cintra, Kaedwen, Kovir, Redenia, Temeria are some of the powerful kingdoms of the Northern Realm. Nilfgaard, the Southern part of the continent, wants to expand its territory by the conquest of the Northern Realm. Their main target is Cintra. To protect the Northern Realm as a whole, the mages of the North decided to defend Cintra. To maintain integrity among all of these kingdoms, there has to be a network infrastructure across the Northern Kingdoms. Although the mages of these kingdoms excel in casting magical spells, they possess no knowledge of networking. Hence, the Brotherhood has assigned your team as the network engineer.
Now your task is to create the network architecture. You are given the table below
which consists of the population of the kingdoms in brackets and the distances between the two kingdoms in each cell.

While creating the network infrastructure there are certain restrictions and rules that you need to follow:
● Choose an appropriate network address and create subnets to assign to each of the kingdoms with the least amount of waste.
● You can use only the odd IP addresses from the available IP range of a network address i.e 192.168.1.0/24 has 256 possible IP addresses, but you can take only 192.168.1.1/24, 192.168.1.3/24, 192.168.1.5/24, etc. as host IP addresses.
● Cintra and the Aedrin kingdoms will need static IP addressing to ensure security. Other kingdoms will use a DHCP server to get IP addresses.
● Cintra will have a Web server and a DNS Server. The website should be accessible using the URL www.cintra.com. Accessing the web server will show the message, “Cintra is in Danger!”.
● Kovir and Redenia kingdoms do not have any database set up. Therefore, these kingdoms each need a printer to print and store essential documents.
● Cintra and Temeria will be communicating a lot. So, an Email Server needs to be set up for sending and receiving emails between these kingdoms.
● Establish connections among all the branches with the shortest route possible. When establishing a connection, keep the following things in mind:
➢ There should be at least one floating route.
➢ You have to remember that the default route cannot be used while
exchanging packets. Data will be delivered using static or dynamic routes only. For an ISP router, you can use the default route but for communicating among the given networks in the above table you have to use static or dynamic routing.
➢ Aedrin, Cintra and Kaedwen kingdoms need to be configured with Dynamic Routing, and the rest of the kingdoms with Static Routing.
● Showing two end devices per network is good enough to represent the whole population.
● You need to be able to ping each branch from another after all the setups are complete.
