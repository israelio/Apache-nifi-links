# Apach-nifi-links
Following is a set of links that i've gather while evaluating NiFi as an ETL tool.

The first place to look for NiFi info would probably be [awesome-nifi](https://github.com/jfrazee/awesome-nifi) but if you didnt find what you are looking for there... here is my additional personal list of links.

## Documentation

[Official Getting Started with Apache NiFi](https://nifi.apache.org/docs/nifi-docs/html/getting-started.html)

[Apache NiFi Expression Language Guide](https://nifi.apache.org/docs/nifi-docs/html/expression-language-guide.html)

[Apache NiFi 1.x Cheatsheet](https://dzone.com/articles/apache-nifi-10-cheatsheet)

[Awesome NiFi List](https://dzone.com/articles/apache-nifi-10-cheatsheet)

[Getting Started with Apache Nifi](http://www.nifi.rocks/getting-started-with-apache-nifi/)

***
## Hortonworks guides

[Getting Started with Apache NiFi](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_getting-started-with-apache-nifi)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_getting-started-with-apache-nifi/bk_getting-started-with-apache-nifi.pdf)

[Apache NiFi User Guide](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_user-guide)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_user-guide/bk_user-guide.pdf)

[Apache NiFi Administration](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_administration)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_administration/bk_administration.pdf)

[Apache MiNiFi Administration](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_minifi-administration)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_minifi-administration/bk_minifi-administration.pdf)

[Apache NiFi Expression Language Guide](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_expression-language)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_expression-language/bk_expression-language.pdf)

[Apache NiFi Developer Guide](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/index.html#bk_developer-guide)
[pdf](https://docs.hortonworks.com/HDPDocuments/HDF3/HDF-3.0.0/bk_developer-guide/bk_developer-guide.pdf)

[Apache NiFi REST API Reference](https://nifi.apache.org/docs/nifi-docs/rest-api/index.html)

[HortonWorks Apachi NiFi videos](https://hortonworks.com/apache/nifi/#section_5)

***
## Articles

[Leveraging Apache NiFi for Agile Dataflows](https://looker.com/blog/leveraging-apache-nifi-for-agile-dataflows)

[Apache NiFi - Records and Schema Registries](https://bryanbende.com/development/2017/06/20/apache-nifi-records-and-schema-registries)

[Introduction to NiFi with WebInterpret](http://tech.webinterpret.com/introduction-to-nifi-with-webinterpret/)

[Apache NiFi - Part 1 (Introduction)](https://www.linkedin.com/pulse/apache-nifi-part-1-introduction-neeraj-sabharwal/)

[Apache NiFi - Part 2 (Twitter Flow)](https://www.linkedin.com/pulse/apache-nifi-part-2-twitter-flow-neeraj-sabharwal/)

[3 considerations for Apache NiFi in Financial Services](https://www.greshamtech.com/blog/3-considerations-for-apache-nifi-in-financial-services)

[HDF/NIFI Best practices for setting up a high performance NiFi installation.](https://community.hortonworks.com/content/kbentry/7882/hdfnifi-best-practices-for-setting-up-a-high-perfo.html)



***
## Json support

[NiFi and JSON](http://www.youritgoeslinux.com/impl/bigdata/nifi/json)

[JSON-to-JSON Simplified with Apache NiFi and Jolt](http://lonnifi.blogspot.co.il/2016/07/json-to-json-simplified-with-nifi-and.html)

[Complex JSON Transformation with Jolt](https://community.hortonworks.com/idea/2150/complext-json-transformation-with-jolt.html)

### Jolt

In order to work with Jolt Json Transformation processor you should be familier with Jolt syntax

[Jolt main page](http://bazaarvoice.github.io/jolt/)

[Jolt Transform Demo](http://jolt-demo.appspot.com/#inception) is a great assistance to check your Jolt expressions

***
## Solutions
[update JSON attributes from different flow file in Apache NiFi](https://tutel.me/c/programming/questions/44704320/need+help+in+update+json+attributes+from+different+flow+file+in+apache+nifi)

[NiFi and HTTP Post Configuration](http://www.tomaszezula.com/2016/10/30/nifi-and-http-post-configuration/)

[A demo collecting wifi admin packets with a raspberry pi, and pushing them to nifi.](https://github.com/simonellistonball/PiWiNiFi)

***
## Development

[Apache Nifi Jira issues](https://issues.apache.org/jira/projects/NIFI/issues/NIFI-4610?filter=allopenissues)

[NiFi Debugging Tutorial](https://community.hortonworks.com/articles/106931/nifi-debugging-tutorial.html)

***
## Interesting NiFi repositories 

### Nifi Deployment

[Apache NiFi - How do I deploy my flow?](https://bryanbende.com/development/2018/01/19/apache-nifi-how-do-i-deploy-my-flow)

[Shell for scripting against Apache NiFi](https://github.com/jdye64/nifi-shell) - Havent managed to get it to work but looked at its code and its interesting.

[NiFi api deploy](https://github.com/aperepel/nifi-api-deploy)

[Update NiFi Flow On-the-Fly via API](https://community.hortonworks.com/articles/3160/update-nifi-flow-on-the-fly-via-api.html)

### Building processors / Additional processors

[nifi-network-processor](https://github.com/abajwa-hw/nifi-network-processor)

[nifi-processor-examples](https://github.com/dstreev/nifi-processor-examples)

[ambari-nifi-service](https://github.com/abajwa-hw/ambari-nifi-service)

[An Ambari Service for NiFi](http://www.redhub.io/lh/ambari-nifi-service/)

[nifi-streaming-examples](https://github.com/bbende/nifi-streaming-examples)

[NiFi-Extensions](https://github.com/fsauer65/NiFi-Extensions)

[nifi-rabbitmq-bundle](https://github.com/MDL/nifi-rabbitmq-bundle)

[nifi_amqp_processors](https://github.com/helicopterman22/nifi_amqp_processors)

[nifi-ConvertJSONtoCSV-bundle](https://github.com/acesir/nifi-ConvertJSONtoCSV-bundle)

### Using NiFi api

[Creating NiFi Template via Rest API](https://community.hortonworks.com/articles/87160/creating-nifi-template-via-rest-api.html)

[Post a NIFI template via REST](https://stackoverflow.com/questions/38446620/post-a-nifi-template-via-rest)

### Learning Nifi

[nifi workshop](https://github.com/aperepel/nifi-workshop)

## Example Dataflow Templates

[NiFi confluence - Example Dataflow Templates](https://cwiki.apache.org/confluence/display/NIFI/Example+Dataflow+Templates)

[HortonWorks nifi templates](https://github.com/hortonworks-gallery/nifi-templates)

[SQL-to-CSV_ExecuteScript](https://gist.github.com/mattyb149/9945663ae9ae5dcb1ddb43d21553204d)

## NiFi blogs

[Apache NiFi official blog](https://blogs.apache.org/nifi/)

[Bryan Bende](https://bryanbende.com/)

[Matt Burgess](http://funnifi.blogspot.co.il/)

[Andy LoPresto](https://alopresto.github.io/)

[ijokarumawak](http://ijokarumawak.github.io/blog/)

[pierre villard](https://pierrevillard.com/)

[richards technotes](https://richardstechnotes.wordpress.com/category/apache-nifi/)




