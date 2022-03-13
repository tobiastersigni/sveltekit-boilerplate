<!DOCTYPE html />
<html lang="en">
    <head>
        <link
            rel="stylesheet"
            href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css"
            integrity="sha512-iBBXm8fW90+nuLcSKlbmrPcLa0OT92xO1BIsZ+ywDWZCvqsWgccV3gFoRBv0z+8dLJgyAHIhR35VZc2oM/gI1w=="
            crossorigin="anonymous"
            referrerpolicy="no-referrer"
        />
        <link
            href="https://unpkg.com/tailwindcss@^2/dist/tailwind.min.css"
            rel="stylesheet"
        />
    </head>

    <body>
        <h3 class="text-center mt-5">Tailwind Search Bar</h3>
        <div class="mt-3 w-1/4 mr-auto ml-auto ">
            <div
                class="px-2 flex items-center border-1 bg-white shadow-sm rounded-full"
            >
                <input
                    class="rounded-l-sm w-full py-2 px-6 text-gray-700 leading-tight focus:outline-none"
                    id="search"
                    type="text"
                    placeholder="Search"
                />
                <div class="p-2">
                    <button
                        class="bg-blue-500 text-white rounded-full p-2 hover:bg-blue-400 focus:outline-none w-12 h-12 flex items-center justify-center"
                    >
                        <i class="fas fa-search" />
                    </button>
                </div>
            </div>
        </div>
    </body>
</html>
