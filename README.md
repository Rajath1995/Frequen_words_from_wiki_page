# WIKI_COMMON_WORDS

The code takes a wiki api json link and return n top common words. 

def find_common_words_from_wiki_page(n: int, page_id: int)->dict:
    """
    The function takes a page id of wiki and return the n top words with title. 
    
    Input Parms:
    n (int): number of top words.
    page_id (int): page id. 
    
    Returns:
    web_scrapped_list (dict): the dict containing all top n word count and Title.
    """
