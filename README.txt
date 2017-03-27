# forum
I want to used MY FORUM-TUTORIAL iN MY PROJECT i WANT TO AMKE IT RESPONSIVE AND ADD SOME VALIDATION IN REGISTRATION
DATABASE 
forum-tutorial
user- 
(user_id(pk),username and password);
topics-
(topic_id(pk), category_id(fk),subctegory_id(fk),author,title,content,date_posted,views,replies)
categories-
(cat_id(pk), category_title)
subcategories-
(subcat_id(pk), parent_id(fk-cat_id), subcategory_title, subcategory_desc)
replies-
(reply_id(pk),category_id(fk),subcategory_id(fk),topic_id(fk),comment,date_posted)
