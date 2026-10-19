# মোবাইল দিয়ে GitHub Pages-এ Starter ZIP আপলোড

1. ZIP ফাইলটি ডাউনলোড করে Android ফোনে রাখুন।
2. GitHub অ্যাপ বা Chrome-এ আপনার GitHub অ্যাকাউন্ট খুলুন।
3. নতুন repository তৈরি করুন: `mr-monjur-multiretailer`।
4. এই ZIP-টি ফোনে Extract করুন। Extract করা ফোল্ডারের ভেতরের ফাইলগুলো repository-তে আপলোড করুন—ZIP ফাইলটিকে শুধু ZIP হিসেবেই আপলোড করলে Pages সরাসরি `index.html` পাবে না।
5. Repository → Settings → Pages → Deploy from a branch → `main` → `/(root)` নির্বাচন করুন এবং Save চাপুন।
6. প্রকাশিত নতুন GitHub Pages লিংকটি পরীক্ষা করুন। পুরোনো দোকানের repository পরিবর্তন করবেন না।

## Subdomain ও নিরাপত্তা
- এই starter-এর slug preview বাস্তব দোকান তৈরি করে না।
- GitHub Pages একা wildcard subdomain routing ও secure tenant provisioning সম্পূর্ণ করে না।
- নিজের ডোমেইন এবং wildcard subdomain-সমর্থিত hosting/routing দরকার হতে পারে।
- Supabase project-এ SQL schema পরীক্ষা করে তারপর প্রয়োগ করুন।
- `service_role` key কখনো HTML/JavaScript-এ রাখবেন না।
- পুরোনো ডেটা migrate করার আগে backup নিন।
