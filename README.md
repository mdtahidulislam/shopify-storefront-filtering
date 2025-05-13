# Storefront Filtering
## filter.filter_scope.attribute.attribute_scope=value

|Filter types name         |filter.|filter_scope .|attribute     |attribute_scope       |=value                  |
|--                        |--     |--            |--            |--                    |--                      |
|Availability              |filter.|v.            |availability. |--                    |=0<br>=1<br>=0,1          |
|Category                  |filter.|p.            |t.category.   |--                    |=id<br>=id1__id2          |
|Price                     |filter.|v             |price.        |lte or gte            |=5         |
|Product tags              |filter.|p.            |tag.          |--                    |=new<br>=new,trending          |
|Product type              |filter.|p.            |product_type. |--                    |=shoes<br>=shoes,belts          |
|Vendor                    |filter.|p.            |vendor.       |--                    |=vendor1<br>=vendor1,vendor2|
|Variant options           |filter.|v.            |option.       |option-name           |=red<br>=red,blue                                                                     |
|Metafields                |filter.|p/v.          |m.            |namespace.key         |=canada<br>=canada,usa                                                                |
|Standard product attribute|filter.|v.            |t.            |shopify.fabric        |=gid://shopify/Metaobject/1<br>=gid://shopify/Metaobject/1, gid://shopify/Metaobject/3|

