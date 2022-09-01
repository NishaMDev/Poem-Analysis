# Poem-Analysis

## Topic - Analysis of Peoms written by two great poets - Slyvia Plath and Rabindranath Tagore.

### Two Poets I used for analysis and comparisons are -

**1. Sylvia Plath**

<img src="https://user-images.githubusercontent.com/89233753/187981728-7b8f7e34-314f-485e-ae20-1b769a697df2.png" width=50% height=45%>

An American poet, novelist, and short-story writer. She is credited with advancing the genre of confessional poetry and is best known for two of her published collections, The Colossus and Other Poems (1960) and Ariel (1965), as well as The Bell Jar, a semi-autobiographical novel published shortly before her death in 1963.

Sylvia Plath's early poems exhibit what became her typical imagery, using personal and nature-based depictions featuring, for example, the moon, blood, hospitals, fetuses, and skulls. Plath's landscape poetry, which she wrote throughout her life, has been described as "a rich and important area of her work that is often overlooked, some of the best of which was written about the Yorkshire moors".

After 1960 her work moved into a more surreal landscape darkened by a sense of imprisonment and looming death, overshadowed by her father. The Colossus is shot through with themes of death, redemption and resurrection. After her husband left, Plath produced, in less than two months, the 40 poems of rage, despair, love, and vengeance on which her reputation mostly rests.

Some in the feminist movement saw Plath as speaking for their experience, as a "symbol of blighted female genius".


**2. Rabindranath Tagore**

<img src="https://user-images.githubusercontent.com/89233753/187981746-1b2af77e-5b67-4088-bad7-0f289ba69948.png" width=50% height=45%>


A Indian Bengali polymath who worked as a poet, writer, playwright, composer, philosopher, social reformer and painter.He reshaped Bengali literature and music as well as Indian art with Contextual Modernism in the late 19th and early 20th centuries. Author of the "profoundly sensitive, fresh and beautiful" poetry of Gitanjali, he became in 1913 the first non-European and the first lyricist to win the Nobel Prize in Literature.

His verse (topic), short stories, and novels were acclaimed their lyricism, colloquialism, naturalism, and unnatural contemplation. His compositions were chosen by two nations as national anthems: India's "Jana Gana Mana" and Bangladesh's "Amar Shonar Bangla". The Sri Lankan national anthem was inspired by his work.

His poems took on a lyrical voice of the moner manush - "man within the heart" and Tagore's "life force of his deep recesses", or meditating upon the jeevan devata—the demiurge or the "living God within".This figure connected with divinity through appeal to nature and the emotional interplay of human drama.


### Work :
In this colab, I have **scraped** 10 poems of each poet from allpoetry.com, extracted POS tags and compared them using various **embedding techniques like Doc2vec , Bert and many more**.

In addition to cleaning, I have **extracted the Nouns, Verbs and Adjective and POS and interchanged them between the poems of two poets based on the similarity score.**

After applying **Latent Dirichlet Allocation (LDA)** and **Latent Semantic Analysis - LSA Topic Modelling** on th swapped and original poems, we observe the following:-

 -  Being the philospher Rabindranath Tagore is, his work clearly shows what he stands for his philosophy for life and nature. 
 -  In the same way, for Sylvia's poems shows deliberated use of details of her everyday life as the raw material for her art. Due to her case of severe depression, we see most of her works revolve around topics that are resonates her feeling of loneliness,anxiety , confusion and yearn for true love (symbol for Tulip).

Finally, we scrape the news online using the identified topics for each poets to understand whether their poems resonates with the news published during that time.
