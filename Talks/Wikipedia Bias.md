
- Wikipedia widely used for NLP models and research
	- missed the number
- Bias well-known
	- Women's articles are shorter, fewer links
	- Research content bias, women's pages disproportionately talked about personal life compared to men
- Wikipedia extremely large, hard to sift it all by hand
	- ID disparities automatically work already
- NLP models can absorb and amplify data biases
- Limitation: confounding variables limit conclusions of analyses
	- sports terms common in men's articles
	- extremely common to have sports player pages
	- not necessarily bias, there's a lot more men footballers than women
	- such artifacts need to be handled in research
- Content disparities
	- binary gender
	- white male editors, people write what they know
	- edit-a-thons & community events observed to help
- Goals:
	- facilitate examinations of systemic diffs in wiki bio articles about people with different attributes
		- create methodologies for (list on slide missed it)
- controlled analysis of social biases in wiki bios
	- selection methodology
	- content analysis methodology
- Reduce confounding variables via Pivot-Slope TF-IDF matching
	- goal: isolate target attrs
	- ()
- construct comparable corpora
	- e.g. set of all cis-men articles, all cis-women articles
	- create corpora with similar distributions of all attributes except gender
- Choice of attrs: Wikipedia categories
	- (Q: have they used wikidata?)
	- worked poorly, favors articles with lots of categories
- constructing comparison corpus
	- used instead TF-IDF vectors with pivot-slope correlation
	- add article with highest-cosign similarity

(Evaluations of random simulations slide)

- Tie in gender via Wikidata
- Race: social construct without global definition
	- skews toward US census of race in the data, using this definition
- gender: split into five by self-identification
- analysis metrics
- Limitations
	- numerous types of bias that our methods don't capture
	- relies on category info that may or may not be comprehensive
	- difficult to determine origins of content disparity
		- (bias by editor, society, historic representation, population skews, etc)

- analysis results: motivating example
	- matched / unmatched
		- articles by common words
		- article length by race
	- more stats
		- breakdown length, edit hist, article age, languages
	- 


