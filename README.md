
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <meta name="description" content="Your very own dashboard to help you manage your online shop.">
    
    <title>Tailwind Sign Up Form</title>
    <!-- Stylesheet -->
    <link rel="stylesheet" href="css/styles.css">
</head>
<body class="bg-gray-200 text-slate-900">
  <!--<div class="max-w-7xl mx-auto bg-white text-gray-700 border-2 border-solid border-gray-100 rounded shadow-lg p-6 my-10">  -->
       <!-- Header: Dashboard into w welcome msg; Quick action toolbar --> 
        <div class="flex">
            <!-- SIDEBAR!! -->
                <aside class="flex flex-col items-center h-screen bg-teal-800 text-neutral-50"> <!-- left nav panel -->
                        <img class="w-[100px] rounded-full mt-7" src="img/profile-picture.webp" alt="A portrait of a woman.">

                        <div class="flex flex-1 flex-col justify-between">
                            <ul class="px-4 py-2"> <!-- On top -->
                            
                                    <li class="px-1 py-2"><a href="#">Dashboard</a></li>
                                    <li class="px-1 py-2"><a href="#">Messages</a></li>
                                    <li class="px-1 py-2"><a href="#">My Listings</a></li>
                                    <li class="px-1 py-2"><a href="#">Orders & Delivery</a></li>
                                    <li class="px-1 py-2"><a href="#">Finances</a></li>
                                    <li class="px-1 py-2"><a href="#">Analytics</a></li>
                                    <li class="px-1 py-2"><a href="#">Settings</a></li>
                            
                            </ul>
                            <ul class="px-4 py-2"> <!-- on bottom -->
                                    <li class="px-1 py-2"><a href="#">Help Center</a></li>
                                    <li class="px-1 py-2"><a href="#">Sign Out</a></li>
                            </ul>
                        </div>
                    </aside>
            <!-- ALL OTHER CONTENT MINUS SIDEBAR : LEFT CONTENT -->
            <div class="flex-1"> 

                <!-- Header -->
                <header class="py-4 text-center bg-zinc-200 text-neutral-700 flex justify-between shadow-lg/20 shadow-teal-900 px-8">
                    <h1 class="font-medium text-3xl pt-3">
                        Welcome Back, Clayton!
                    </h1>
                    <div class="border rounded-lg px-3 py-0.5 border-zinc-400">
                        <h2 class="italic">Quick Actions Toolbar:</h2>
                        <ul class="flex gap-4">
                            <!-- each has to have an icon  -->
                
                            <li><a class="text-sm inline-flex gap-1 items-center" href="#">
                
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M12 9v6m3-3H9m12 0a9 9 0 1 1-18 0 9 9 0 0 1 18 0Z" />
                                </svg>
                                Add New Listing
                            </a></li>
                            <li><a href="#" class="inline-flex gap-1 items-center">
                
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M13.5 21v-7.5a.75.75 0 0 1 .75-.75h3a.75.75 0 0 1 .75.75V21m-4.5 0H2.36m11.14 0H18m0 0h3.64m-1.39 0V9.349M3.75 21V9.349m0 0a3.001 3.001 0 0 0 3.75-.615A2.993 2.993 0 0 0 9.75 9.75c.896 0 1.7-.393 2.25-1.016a2.993 2.993 0 0 0 2.25 1.016c.896 0 1.7-.393 2.25-1.015a3.001 3.001 0 0 0 3.75.614m-16.5 0a3.004 3.004 0 0 1-.621-4.72l1.189-1.19A1.5 1.5 0 0 1 5.378 3h13.243a1.5 1.5 0 0 1 1.06.44l1.19 1.189a3 3 0 0 1-.621 4.72M6.75 18h3.75a.75.75 0 0 0 .75-.75V13.5a.75.75 0 0 0-.75-.75H6.75a.75.75 0 0 0-.75.75v3.75c0 .414.336.75.75.75Z" />
                                </svg>
                                View shop
                            </a>
                            </li>
                
                            <li><a href="#" class="inline-flex gap-1 items-center">
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 13.5h3.86a2.25 2.25 0 0 1 2.012 1.244l.256.512a2.25 2.25 0 0 0 2.013 1.244h3.218a2.25 2.25 0 0 0 2.013-1.244l.256-.512a2.25 2.25 0 0 1 2.013-1.244h3.859m-19.5.338V18a2.25 2.25 0 0 0 2.25 2.25h15A2.25 2.25 0 0 0 21.75 18v-4.162c0-.224-.034-.447-.1-.661L19.24 5.338a2.25 2.25 0 0 0-2.15-1.588H6.911a2.25 2.25 0 0 0-2.15 1.588L2.35 13.177a2.25 2.25 0 0 0-.1.661Z" />
                                </svg>
                                View Inbox
                            </a>
                            </li>
                            <li><a href="#" class="inline-flex gap-1 items-center">
                
                                <svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke-width="1.5" stroke="currentColor" class="size-6">
                                    <path stroke-linecap="round" stroke-linejoin="round" d="M2.25 18.75a60.07 60.07 0 0 1 15.797 2.101c.727.198 1.453-.342 1.453-1.096V18.75M3.75 4.5v.75A.75.75 0 0 1 3 6h-.75m0 0v-.375c0-.621.504-1.125 1.125-1.125H20.25M2.25 6v9m18-10.5v.75c0 .414.336.75.75.75h.75m-1.5-1.5h.375c.621 0 1.125.504 1.125 1.125v9.75c0 .621-.504 1.125-1.125 1.125h-.375m1.5-1.5H21a.75.75 0 0 0-.75.75v.75m0 0H3.75m0 0h-.375a1.125 1.125 0 0 1-1.125-1.125V15m1.5 1.5v-.75A.75.75 0 0 0 3 15h-.75M15 10.5a3 3 0 1 1-6 0 3 3 0 0 1 6 0Zm3 0h.008v.008H18V10.5Zm-12 0h.008v.008H6V10.5Z" />
                                </svg>
                                Go to Earnings
                            </a></li>
                        </ul>
                    </div>
                </header> <!-- End Header -->

                <!-- Main CONTENT -->
                <main class="container mx-auto px-7 mt-6">
                    <h2 class="font-bold text-3xl text-teal-600 pb-2 ">Overview</h2> <!-- would this be h2? -->
                    <p class="pb-5">Here's a quick glance at how your shop is doing today.</p>
                
                <div class="flex gap-2 container px-3 items-stretch">
                    
                        <!-- key metrics -->
                        <section class="flex-2 p-4 bg-zinc-100 rounded-lg shadow-lg/30 overflow-hidden">
                            <h3 class="font-semibold text-lg pt-1 pb-3">Key Metrics</h3>
                            <div class="grid grid-cols-2 gap-4">
                                <section class="bg-gray-200 rounded-lg px-6 pb-5 pt-4"> <!-- border border-teal-200 rounded-md p-3 flex flex-col justify-between text-sm bg-white -->
                            
                                    <h4 class="text-zinc-500 pb-1 text-sm">Sales This Month</h4>
                                    <p class="font-semibold text-xl pb-1 text-zinc-700">$2,450 CAD</p>
                                    <p class="text-xs text-green-700 italic">+12% from last month</p>
                                </section>
                                <section class="bg-gray-200 rounded-lg px-6 pb-5 pt-4">
                                    <h4 class="text-zinc-500 pb-1 text-sm">Orders Pending</h4>
                                    <p class="text-xl text-zinc-700 font-light"><span class="font-semibold text-xl">4 orders</span> awaiting fulfilment</p>
                                </section>
                                <section class="bg-gray-200 rounded-lg px-6 pb-5 pt-4">
                                    <h4 class="text-zinc-500 pb-1 text-sm">Shipped Orders</h4>
                                    <p class="text-xl text-zinc-700 font-light"><span class="font-semibold text-xl">8 orders</span> shipped</p>
                                </section>
                                <section class="bg-gray-200 rounded-lg px-6 pb-5 pt-4">
                                    <h4 class="text-zinc-500 pb-1 text-sm">Shop Visits Today</h4>
                                    <p class="text-xl text-zinc-700 font-light"><span class="text-xl font-semibold">162 </span> visitors</p>
                                </section>

                                <!-- Alert Section do later -->
                                <section class="bg-gray-200 col-span-2 rounded-lg px-6 pb-5 pt-4">
                                    <h4 class="text-zinc-500 pb-1 text-sm">Low‑Stock Alerts</h4>
                                    <ul class="text-xl text-zinc-700 font-light">
                                        <li>Terracotta Planter <span class="text-xs italic text-red-500">– only 2 left</span></li>
                                        <li>Wheel‑Thrown Trinket Bowl <span class="text-xs italic text-red-500">– only 1 left</span></li>
                                    </ul> 
                                </section>
                            </div>
                        </section><!-- end of key metrics section -->
                    
                    
                        <!-- unread messages section-->
                        <section class="p-4 bg-zinc-100 rounded-lg shadow-lg/30 overflow-hidden flex-3">
                            <h3 class="font-semibold text-lg pt-1 pb-3">Unread Messages</h3>
                            <div class="flex flex-col gap-2"> <!-- container of all messages -->

                                <!-- message 1 -->
                                <div class="bg-gray-200 rounded-lg pt-4 border-b border-b-zinc-400 pb-4 flex">
                                    <div class="text-sm text-zinc-700 leading-relaxed pl-4 pr-3 border-r border-r-zinc-300">
                                        <p class="text-zinc-500 pb-1 text-sm"><span class="italic">Subject:</span> Glaze Food-Safety Question</p>
                                        <div class="flex justify-between gap-3 pb-1">
                                            <p class="text-xs font-semibold text-zinc-600"><span class="italic">From:</span> Dana Stone</p>
                                            <p class="text-xs font-semibold text-zinc-600"><span class="italic">Date:</span> October 19, 2025</p>
                                        </div>
                                        <p>
                                        Hi Clayton, I purchased your Reactive Glaze Dinner Plate last month and was wondering if it’s certified
                                        food-safe for daily use. I want to make sure it won’t leach any chemicals when I eat off it.
                                        </p>
                                    </div>
                                    <div class="px-3 shrink-0">
                                        <ul class="flex flex-col justify-start gap-2 text-xs text-center">
                                        <li class="border rounded-xl px-2 py-1 bg-teal-700 text-white hover:bg-teal-800">
                                            <a href="#">Reply</a>
                                        </li>
                                        <li class="bg-gray-200 text-gray-800 hover:bg-gray-300 border rounded-xl px-2 py-1">
                                            <a href="#">Mark as Read</a>
                                        </li>
                                        <li class="border rounded-xl px-2 py-1 bg-red-100 text-red-700 hover:bg-red-200">
                                            <a href="#">Delete</a>
                                        </li>
                                        </ul>
                                    </div>
                                </div>
                                <!-- end message 1 -->

                                <!-- message 2 -->
                                <div class="bg-gray-200 rounded-lg pt-4 border-b border-b-zinc-400 pb-4 flex gap-6">
                                <div class="text-sm text-zinc-700 leading-relaxed pl-4">
                                    <p class="pb-0.5 text-lg text-zinc-950"><span class="italic">Subject:</span> Custom Initials on Mugs</p>
                                    <div class="flex justify-between gap-3 text-shadow-md pb-1">
                                    <p class="text-sm font-semibold text-zinc-600">From: Lee Parker</p>
                                    <p class="text-sm font-semibold text-zinc-600">Date: October 20, 2025</p>
                                    </div>
                                    <p>
                                    Hello Clayton, I’d love to order four of your hand-glazed mugs with my initials “L.P.” stamped on the base.
                                    Is that something you can accommodate, and how much extra would it cost?
                                    </p>
                                </div>
                                <!-- action buttons 2 -->
                                <div class="px-3 shrink-0">
                                    <ul class="flex flex-col justify-start gap-2 text-xs text-center">
                                    <li class="border rounded-xl px-2 py-1 bg-teal-700 text-white hover:bg-teal-800 text-center">
                                        <a href="#">Reply</a>
                                    </li>
                                    <li class="bg-gray-200 text-gray-800 hover:bg-gray-300 border rounded-xl px-2 py-1">
                                        <a href="#">Mark as Read</a>
                                    </li>
                                    <li class="border rounded-xl px-2 py-1 bg-red-100 text-red-700 hover:bg-red-200">
                                        <a href="#">Delete</a>
                                    </li>
                                    </ul>
                                </div>
                                </div>
                                <!-- end message 2 -->

                                <!-- message 3 -->
                                <div class="bg-gray-200 rounded-lg pt-4 pb-4 flex gap-6">
                                    <!-- message content 3 -->
                                    <div class="text-sm text-zinc-700 leading-relaxed pl-4">
                                        <p class="pb-0.5 text-lg text-zinc-950"><span class="italic">Subject:</span> Shipping Timeline for Order #1021</p>
                                        <div class="flex justify-between gap-3 text-shadow-md pb-1">
                                        <p class="text-sm font-semibold text-zinc-600">From: Morgan Lee</p>
                                        <p class="text-sm font-semibold text-zinc-600">Date: October 22, 2025</p>
                                        </div>
                                        <p>
                                        Hello Clayton, I’m excited to receive the three mugs I ordered (Order #1021). Could you let me know when you
                                        expect it to ship? I need it for my girlfriend's birthday next Friday.
                                        </p>
                                    </div>

                                    <!-- Actions Buttons 3 -->
                                    <div class="px-3 shrink-0">
                                        <ul class="flex flex-col justify-start gap-2 text-xs text-center">
                                        <li class="border rounded-xl px-2 py-1 bg-teal-700 text-white hover:bg-teal-800">
                                            <a href="#">Reply</a>
                                        </li>
                                        <li class="bg-gray-200 text-gray-800 hover:bg-gray-300 border rounded-xl px-2 py-1">
                                            <a href="#">Mark as Read</a>
                                        </li>
                                        <li class="border rounded-xl px-2 py-1 bg-red-100 text-red-700 hover:bg-red-200">
                                            <a href="#">Delete</a>
                                        </li>
                                        </ul>
                                    </div>
                                </div>
                                <!-- end message 3 -->

                            </div>
                        </section>

                    
                         <!-- flexed orders and items section -->
                        <div class="flex flex-col gap-2 flex-2">
                             <!-- recent orders section -->
                              <section class="p-4 bg-zinc-100 rounded-lg shadow-lg/30 overflow-hidden">
                                <h3 class="font-semibold text-lg pt-1 pb-3">Recent Orders</h3>
                                <ol>
                                    <li>
                                        <h4>Order #1023</h4>
                                        <ul>
                                            <li>4 × Porcelain Serving Bowls</li>
                                            <li>Status: Processing</li>
                                        </ul>
                                    </li>
                                    <li>
                                        <h4>Order #1022</h4>
                                        <ul>
                                            <li>1 × Hand‑glazed Teapot</li>
                                            <li>Status: Shipped</li>
                                        </ul>
                                    </li>
                                    <li>
                                        <h4>Order #1021</h4>
                                        <ul>
                                            <li>2 × Handcrafted Ceramic Mug</li>
                                            <li>Status: Delivered</li>
                                        </ul>
                                    </li>
                                </ol>
                                <a href="#">View All Orders</a>
                              </section> <!-- end of recent orders section -->

                              <!-- Top Selling Items Section (possibly don't flex this with the others? It can be a popped somewhere) -->   

                              <section class="p-4 bg-zinc-100 rounded-lg shadow-lg/30 overflow-hidden">
                                <h3 class="font-semibold text-lg pt-1 pb-3">Top Selling Items</h3>
                                <ol>
                                    <li><span class="font-bold">Handcrafted Ceramic Mug</span> – 35 units sold</li>
                                    <li><span class="font-bold">Reactive Glaze Dinner Plate</span> – 27 units sold</li>
                                    <li><span class="font-bold">Knitted Scarf</span> – 19 units sold</li>
                                </ol>
                              </section> <!-- end of top selling items section -->
                        </div>
                </div>
                </main>
            </div>


        </div>
   <!--  </div> -->
</body>
</html>