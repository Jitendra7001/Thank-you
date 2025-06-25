# Thank-you
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thank You!</title>
    <!-- Tailwind CSS CDN for easy styling -->
    <script src="https://cdn.tailwindcss.com"></script>
    <style>
        /* Custom font for a clean look */
        body {
            font-family: 'Inter', sans-serif;
        }
        /* Custom animations */
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: scale(0.9);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        .animate-fade-in {
            animation: fadeIn 1s ease-out forwards;
        }
    </style>
</head>
<body class="bg-gradient-to-br from-green-400 to-blue-500 min-h-screen flex items-center justify-center p-4">
    <!-- Main container for the thank you content -->
    <div class="bg-white p-8 rounded-xl shadow-2xl max-w-md w-full text-center animate-fade-in">
        <!-- Thank you message heading -->
        <h1 class="text-5xl font-extrabold text-gray-900 mb-4">
            Thank You for Your Purchase!
        </h1>

        <!-- Confirmation message -->
        <p class="text-xl text-gray-700 mb-6">
            Your order has been successfully placed and is being processed.
        </p>

        <!-- Optional additional information -->
        <p class="text-md text-gray-600 mb-8">
            You will receive a confirmation email shortly with your order details.
        </p>

        <!-- Button to go back to the home/landing page -->
        <a href="index.html" class="inline-block bg-blue-600 hover:bg-blue-700 text-white font-bold py-3 px-6 rounded-lg shadow-md transition duration-300 ease-in-out transform hover:scale-105">
            Back to Home
        </a>
    </div>
</body>
</html>
