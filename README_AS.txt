DARIKA GOAT FARM OFFLINE APP — ব্যৱহাৰৰ নিয়ম

ফাইলসমূহ:
- index.html: মূল App
- manifest.webmanifest: install/PWA তথ্য
- sw.js: offline cache
- README_AS.txt: এই নিৰ্দেশনা

গুৰুত্বপূৰ্ণ:
1) App-টো প্ৰথমে ইণ্টাৰনেট থকা অৱস্থাত HTTPS website বা localhost-ত এবাৰ খোলক। তেতিয়াহে service worker-এ App-ৰ ফাইল cache কৰি offline খোলাত সহায় কৰিব।
2) কেৱল ZIP extract কৰি index.html file-টো tap কৰি খোলাৰ ক্ষেত্ৰত মূল App চলিব পাৰে, কিন্তু install/offline caching browser-ভেদে সীমিত হ’ব পাৰে।
3) এই App-ত ডেটা প্ৰতিটো ডিভাইচৰ browser local storage-ত থাকে। মোবাইল আৰু কম্পিউটাৰত স্বয়ংক্ৰিয়ভাৱে sync নহয়। Backup / Settings > Export Full Backup কৰি JSON ফাইলটো আন ডিভাইচলৈ পঠিয়াই Import কৰক।
4) Browser data clear কৰিলে App-ৰ ডেটা হেৰাব পাৰে। নিয়মিত backup লওক।
5) আগতে ভৰোৱা 13টা goat name আৰু PPR-ৰ নোটবোৰ আগৰ কথোপকথনৰ তথ্যৰ পৰা দিয়া হৈছে; ৰেকৰ্ড ব্যৱহাৰ কৰাৰ আগতে সঠিকতা পৰীক্ষা কৰক।
6) ভেকচিনৰ সময়, dose আৰু গৰ্ভৱতী ছাগলীৰ টিকাকৰণ veterinary doctor-ৰ পৰামৰ্শ অনুসৰি কৰিব।

মোবাইল/কম্পিউটাৰত install:
- ZIP extract কৰক।
- ফাইলসমূহ একেটা folder-ত ৰাখক।
- App-টো HTTPS-ত উপলব্ধ হ’লে Chrome/Edge-ত খোলক।
- Chrome menu > Install app / Add to Home screen বাছক।
