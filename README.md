## ElasticSuite Blog search for MageFan_Blog


This module connecting between each other [ElasticSuite](https://github.com/Smile-SA/elasticsuite) search extension and MageFan Blog extension for Magento 2 (https://magefan.com/magento2-blog-extension , https://github.com/magefan/module-blog)

It allows to index Blog posts into the search engine and display them into the autocomplete results, and also on the search result page.

### Requirements

* For version 1.x.x: Magento Community Edition 2.2.* or Magento Enterprise Edition 2.2.*
* For version 2.x.x: Magento Community Edition 2.3.* or Magento Enterprise Edition 2.3.*

The module requires :

- [ElasticSuite](https://github.com/Smile-SA/elasticsuite)
- [MageFanBlog](https://github.com/magefan/module-blog)

### How to use

1. Enable it

``` bin/magento module:enable Comwrap_ElasticsuiteBlog ```

3. Install the module and rebuild the DI cache

``` bin/magento setup:upgrade ```

4. Process a full reindex of the Blog Post search index

``` bin/magento index:reindex elasticsuite_blog_fulltext ```

