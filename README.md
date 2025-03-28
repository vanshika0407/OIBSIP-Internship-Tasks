# OIBSIP-Internship-Tasks
This repository contains all the tasks completed during my Web Development and Design Internship at OASIS INFOBYTE (OIBSIP). The tasks are categorized based on different levels, and each task includes well-structured source code, documentation, and a demo video showcasing my work.

### Landing Page ####

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Luxury Gift Landing Page</title>
    <script src="https://cdn.tailwindcss.com"></script>
</head>
<body class="bg-gray-100">
    <div class="max-w-5xl mx-auto bg-white shadow-xl rounded-lg overflow-hidden mt-10">
        <!-- Header Section -->
        <div class="relative h-96">
            <img src="https://i.pinimg.com/236x/8b/2b/59/8b2b59f7bd000e6795d76afd4eb92a15.jpg" class="w-full h-full object-cover" alt="Luxury Gifts">
            <div class="absolute inset-0 bg-black bg-opacity-40 flex flex-col justify-center items-center text-white">
                <h1 class="text-4xl font-extrabold">Luxury Gifts, Thoughtfully Curated</h1>
                <p class="mt-3 text-lg">Discover a collection of beautifully designed gifts for every occasion.</p>
                <button class="mt-6 bg-red-500 text-white py-3 px-8 rounded-lg text-lg font-semibold shadow-md hover:bg-red-600 transition">Shop Now</button>
            </div>
        </div>
        
        <!-- Features Section -->
        <div class="grid grid-cols-1 md:grid-cols-3 gap-8 p-10 text-center">
            <div class="p-6 bg-gray-100 rounded-lg shadow-md relative bg-cover bg-center" style="background-image: url('https://www.shutterstock.com/image-vector/premium-quality-vector-badges-luxury-260nw-1554480626.jpg');">
                <div class="bg-white bg-opacity-80 p-4 rounded-md">
                    <h2 class="text-2xl font-bold text-gray-800">🌟 Premium Quality</h2>
                    <p class="text-gray-600 mt-2">Hand-picked gifts with top-tier materials.</p>
                </div>
            </div>
            <div class="p-6 bg-gray-100 rounded-lg shadow-md relative bg-cover bg-center" style="background-image: url('https://images.unsplash.com/photo-1695654390723-479197a8c4a3?fm=jpg&q=60&w=3000&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxzZWFyY2h8OHx8bGFzdCUyMG1pbGUlMjBkZWxpdmVyeXxlbnwwfHwwfHx8MA%3D%3D');">
                <div class="bg-white bg-opacity-80 p-4 rounded-md">
                    <h2 class="text-2xl font-bold text-gray-800">🚀 Fast Delivery</h2>
                    <p class="text-gray-600 mt-2">We ensure quick and safe delivery.</p>
                </div>
            </div>
            <div class="p-6 bg-gray-100 rounded-lg shadow-md relative bg-cover bg-center" style="background-image: url('https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSeOTqwgIXiLziYQDRPV-zBb-eVs_dhR3n9LQ&s');">
                <div class="bg-white bg-opacity-80 p-4 rounded-md">
                    <h2 class="text-2xl font-bold text-gray-800">🎁 Gift Customization</h2>
                    <p class="text-gray-600 mt-2">Personalize your gifts for a unique touch.</p>
                </div>
            </div>
        </div>
        <!-- Call to Action -->
        <div class="text-center py-10">
            <h2 class="text-3xl font-bold text-gray-800">Make Every Moment Special</h2>
            <p class="text-lg text-gray-600 mt-3">Choose from a variety of luxurious gifts for your loved ones.</p>
            <button class="mt-5 bg-red-500 text-white py-3 px-10 rounded-lg text-lg font-semibold shadow-md hover:bg-red-600 transition">Explore Now</button>
        </div>
    </div>
</body>
</html>
