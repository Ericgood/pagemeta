pagemeta
========

Extract web page html meta

    url = 'http://blog.afaker.com/'
    meta = extractor.get_pagemeta(url)
    self.assertTrue(meta['title'] != None)
