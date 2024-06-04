filters:: {"welcome" false, "🏡 welcome" false}

- {{query (page-property :type "video")}}
  query-table:: true
  query-properties:: [:title :creator :status :topics :language :link]