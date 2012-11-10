CouchDB
========

# Learning CouchDB
## Node.js Taiwan Workshop 2012
* cloud hosting 
    * [Cloundant](https://cloudant.com/) 
    * [Pillow](https://github.com/khellan/Pillow)
    
* Resource
    * [Cradle - couchDB client for node.js](https://github.com/cloudhead/cradle)

* feature
    * 提供多版本的存儲,方便找回舊資料(跟MongoDB不同)
    * 但是如果你的資料是會經常做UPDATE的，使用CouchDB會造成版本過多，空間消耗過大。可以設nocache屬性，關閉這個資料的版本控管
    * Map Reduce
        * Map: interate every object to extract data you need.
        * Reduce : reduce every object instance key into single value.(reduce the number of Map item)
