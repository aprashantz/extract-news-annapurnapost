#### What does this script do?

Can extract all the available news article on a particular search topic from **Annapurna Post**.

#### Manual task needed to run:

Change this variable as per the search topic.

```sh
news_topic = "डेंगु"
```

Now when you run the **main.py** script, new file with **डेंगु.json** will be created with information as shown in example below:

```sh
{
  "fetched_upto": 1,
  "total_page": 1,
  "articles": [
        {
            "title": "पाकिस्तानमा बढ्यो डेँगुको प्रकोप, एकै दिन ५ जनाको मृत्यु",
            "content": "पाकिस्तानमा केही महिना यतादेखि सुरु भएको डेँगुको प्रकोप झन् बढेको पाइएको यहाँका स्वास्थ्य अधिकारीहरुले जानकारी दिएका छन् । ती अधिकारीका अनुसार पाकिस्तानका पूर्वी प्रान्त पञ्जावमा पछिल्लो समयमा यसको प्रकोप बढेको पाइएको छ । पञ्जावमा मात्र आइतबार चार जनाको ज्यान गएको बताइएको छ । त्यसैगरी सिन्ध प्रान्तमा अर्का एकजनाको ज्यान गएको छ"
        },
        {
            "title": "डेंगुबाट हालसम्म ५४ को मृत्यु, ४६७६८ मा संक्रमण",
            "content": "डेंगु संक्रमण ७७ वटै जिल्लामा फैलिएको छ। डेंगुबाट हालसम्म ५४ जनाको मृत्यु भएको स्वास्थ्य तथा जनसङ्ख्या मन्त्रालयले जनाएको छ। पछिल्लो २४ घण्टामा डेंगुबाट थप दुई जनाको मृत्यु भएको छ।"
        }

    ]
}
```
