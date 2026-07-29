# Comparative Co-Occurrence Network Analysis of the New Testament Gospels and the Qur'an

**Erin Brzusek**  
Georgetown University

# Abstract

This study seeks to analyze textual data from the four New Testament Gospels (Matthew, Mark, Luke, and John) and the Qur'an to construct and compare co-occurrence networks. The goal of this project is to evaluate how the distinct literary styles of chronological narrative and thematic discourse alter the structure of the resulting networks despite the shared figures between the texts. Because the Bible and Qur'an differ substantially in both length and organization, this study constructs a series of comparable character co-occurrence networks using multiple textual proximity definitions. The resulting networks are then evaluated through analyses of global topology, node centrality, degree distributions, and community structure.

![Comparison of the Gospel and Qur'an character networks](images/side_by_side_networks.png)

## Repository Structure

```
├── index.qmd        
├── index.pdf     
├── references.bib   
├── images/      
├── social_network_analysis.ipynb                 
└── README.md              
```

# Introduction

Practitioners of Abrahamic religions make up over half the world’s population ^[According to the *World Population Review*, 32% of the global population identify as Christian, 25% Muslim and 0.2% Jewish], and the holy texts of these faiths serve as the cornerstone for their respective beliefs and cultural traditions. Despite historical and modern-day contention between Christianity and Islam, the New Testament Gospels and the Qur’an have a deeply interconnected lineage. Shared figures bridge them conceptually, but the texts themselves are structured in fundamentally different ways. The four New Testament Gospels (Matthew, Mark, Luke, and John) are framed primarily as chronological narratives^[A chronological narrative is a type of storytelling that presents events in the order they occur in time, following a linear progression from beginning to end], whereas the Surahs of the Qur’an are formatted as a thematic discourse^[Its narratives use a literary style to convey moral and spiritual lessons, focusing on ethical, spiritual, and religious purposes rather than historical accuracy].

| Luke Chapter 2 KJV | Qur'an Surah 19 Sahih International |
|:---:|:---:|
| ![Luke Chapter 2 KJV](images/bible_luke.png) | ![Qur'an Surah 19 Sahih International](images/quran_surah19.png) |

**The Immaculate Conception as Chronological Narrative and Thematic Discourse**

This study analyzes textual data from both the Bible and Qur'an to construct, visualize, and compare their underlying character networks. Specifically, this study evaluates how these distinct literary styles alter the resulting graph topology among shared entities. Because the Bible and Qur'an differ substantially in both length and organization, this study constructs a series of comparable character co-occurrence networks using multiple textual proximity definitions. The resulting networks are then evaluated through analyses of global topology, node centrality, degree distributions, and community structure. Data for this study is drawn from the BibleData repository for the Gospels[@noauthor_bibledata_nodate] and the Sahih International English translation via the Qur’an API[@network_api_nodate].

This paper seeks to address three central research questions:

- To what extent do differences in literary organization correspond to differences in character network topology?
- How does the relative importance of shared characters change across the two character networks?
- Do both networks exhibit power-law degree distributions despite their fundamental structural differences?

Ultimately, this comparative network analysis serves to show that the shared principal figures rise above the structural settings of their respective texts. Beyond religious and literary divides, these texts represent a shared foundation of human hope and eternal faith.