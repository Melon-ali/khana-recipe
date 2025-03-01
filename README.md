# khana-recipe

# khana-recipe

✓ Your home page has been made SEO Friendly and all the content of the home page is a server component.

✓ Login and register have been implemented.

✓ Clicking on the recipe cards on the home page will take you to the details page of that recipe.

✓ Clicking on the categories on the home page will take you to a separate page and only the recipes of that category will be shown there.

✓ There is a Favorite button on the recipe details page, clicking there will save that recipe as a Favorite. However, the Favorite button will only work in the Logged In state. In this case, the IDs of the Favorite recipes should be kept in the Users Collection in String form. Something like this -

[
{
// ... Other Properties of user
"favourites": ["66233de62d53857e7cedc656"]
}
]
✓ You can share the recipe on various Social Media by clicking on the Share button on the recipe details page.

✓ You need to update the Meta Data on the Recipe Details page properly.

✓ You have been given some sample data in the dist/data folder. Following this sample data structure, you will use Mongoose and MongoDB to do all the database related tasks as shown in the module. Here are some very important things - your database name should be "khanaKhazana". The collection name should be "recipes" and the user collection name to store user data should be "users".

✓ The MongoDB database must be hosted on Mongo Atlas as shown to you in the module. If you install MongoDB on your local machine and use local connection, it will not be acceptable to us. The database connection details must be kept in the .env file and must be removed from this .env file .gitignore so that when we review your project, we can see the connection details of the .env file and run it. Otherwise, you will not get marks in the assignment.

✓ Not Found and Error pages must be handled properly.


✓ আপনাকে হোম পেজটি SEO Friendly ভাবে বানানো হয়েছে এবং হোম পেজের সব কন্টেন্ট যেন সার্ভার কম্পোনেন্ট হয় ।

✓ লগইন এবং রেজিস্টার এর Implement করা হয়েছে ।

✓ হোম পেজের রেসিপি কার্ড গুলোতে ক্লিক করলে সেই রেসিপি এর ডিটেইলস পেজে নিয়ে যাবে ।

✓ হোম পেজের ক্যাটেগরি গুলোতে ক্লিক করলে, আলাদা পেজে নিয়ে যাবে এবং সেখানে শুধু মাত্র সেই ক্যাটেগরি এর রেসিপি গুলো দেখাবে ।

✓ রেসিপি ডিটেইলস পেজে Favourite বাটন রয়েছে, সেখানে ক্লিক করলে সেই রেসিপি Favourite হিসেবে Save হবে । তবে শুধু Logged In অবস্থাতেই Favourite বাটন কাজ করবে । এক্ষেত্রে Users Collection এ Favourite রেসিপি এর ID গুলো String আকারে রাখতে হবে। অনেকটা এভাবে -

[
  {
    // ... Other Properties of user
    "favourites": ["66233de62d53857e7cedc656"]
  }
]
✓ রেসিপি ডিটেইলস পেজে শেয়ার বাটনে ক্লিক করে রেসিপি বিভিন্ন Social Media তে শেয়ার করতে পারবে ।

✓ রেসিপি ডিটেইলস পেজে এর Meta Deta গুলো সঠিক ভাবে আপডেট করতে হবে ।

✓ আপনাদের কিছু sample data দিয়ে দেয়া হয়েছে dist/data ফোল্ডারে । এই sample data structure ফলো করে আপনারা Mongoose এবং MongoDB ব্যবহার করে ডেটাবেজ সম্পর্কিত সকল কাজ গুলো করবেন ঠিক যেভাবে মডিউলে দেখানো হয়েছে । এখানে কিছু বিষয় খুবই গুরুত্বপূর্ণ - আপনাদের ডেটাবেজ এর নাম হতে হবে "khanaKhazana" । Collection এর নাম হতে হবে "recipes" এবং ইউজার ডেটা রাখার জন্যে ইউজার এর কালেকশন এর নাম হতে হবে "users" ।

✓ MongoDB ডাটাবেস অবশ্যই Mongo Atlas এ হোস্ট করতে হবে ঠিক যেভাবে আপনাদেরকে মডিউলে দেখিয়ে দেয়া হয়েছে। আপনি লোকাল মেশিনে MongoDB ইন্সটল করে লোকাল কানেকশন ইউজ করলে আমাদের কাছে গ্রহণযোগ্য হবেনা। ডাটাবেস কানেকশন ডিটেইলস অবশ্যই .env ফাইলে রাখবেন এবং অবশ্যই অবশ্যই এই .env ফাইল .gitignore থেকে সরিয়ে দিবেন যেন আমরা যখন আপনার প্রজেক্ট রিভিউ করবো, তখন যেন .env ফাইলের কানেকশন ডিটেইলস দেখতে পাই এবং রান করে দেখতে পারি। এর ব্যতিক্রম হলে আপনি এসাইনমেন্টে মার্ক পাবেন না।

✓ Not Found এবং Error পেজ ঠিক ভাবে হ্যান্ডেল করতে হবে ।
