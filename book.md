# Further Text Analysis of Gray's Anatomy

On this page, a thorough analysis of "Gray's Anatomy (41st edition)" textbook can be found.
The book, sections, and chapters have been analyzed individually, and the results are displayed in tables below.
There are word clouds for every section displaying the most unique words for each section (using TF-IDF) .
For the chapters, the 10 most common words are displayed at the bottom.

Please read the text analysis on the home page before going through the results on this page, thank you.

## Book

The whole textbook text was analyzed and considered on the home page.
Table 1 shows the results of the analysis, and the results here are the overall results of the sections and chapters that are seen below.

Text  |	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	long words (10+)	|	% of text	|	Long Words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
--- |	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
Gray's Anatomy	|	1084200	|	46554	|	23.29	|	24552	|	2.26%	|	109598	|	10.11%	|	8930	|	0.82%	|	299	|	0.03%	|	456496	|	42.10%	|	56	| 5.24

> Table 1: The text analysis of the book, as seen on the home page.

## Sections

The textbook is divided into 9 sections, with the first 3 sections going through fundamentals of the body, and the last 6 sections going through body parts in great details.
Each section consists of a certain number of chapters (analyzed further below) of varying lengths and have different authors and editors.

### Results

First, let's start by looking at the statistics of each section of the textbook.
Table 2 shows the results of the text analysis that was done similarly for the entire textbook and Wikipedia pages.

It can be seen that there is little variance between the sections in terms of the word statistics,
though there are some sections that seem to be a little easier to read than others.
The lexical richness does seem to vary a bit from chapter to chapter, even when taking into consideration the amount of words, which is quite interesting.
Maybe the authors are writting differently after all.

Section	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
1	|	Cells, tissues and systems	|	129846	|	5880	|	22.08	|	9770	|	7.52%	|	16191	|	12.47%	|	1141	|	0.88%	|	78	|	0.06%	|	52426	|	40.38%	|	58	|	5.29
2	|	Embryogenesis	|	41546	|	1669	|	24.89	|	4994	|	12.02%	|	5151	|	12.40%	|	356	|	0.86%	|	30	|	0.07%	|	17423	|	41.94%	|	59	|	5.30
3	|	Neuroanatomy	|	127041	|	5499	|	23.10	|	7744	|	6.10%	|	15058	|	11.85%	|	1347	|	1.06%	|	57	|	0.04%	|	51822	|	40.79%	|	59	|	5.24
4	|	Head and neck	|	251863	|	10570	|	23.83	|	10548	|	4.19%	|	22827	|	9.06%	|	2125	|	0.84%	|	23	|	0.01%	|	108306	|	43.00%	|	56	|	5.22
5	|	Back	|	48097	|	2165	|	22.22	|	4042	|	8.40%	|	4208	|	8.75%	|	292	|	0.61%	|	3	|	0.01%	|	20284	|	42.17%	|	55	|	5.23
6	|	Pectoral girdle and upper limb	|	88788	|	3890	|	22.82	|	4257	|	4.79%	|	7326	|	8.25%	|	782	|	0.88%	|	14	|	0.02%	|	38332	|	43.17%	|	53	|	5.22
7	|	Thorax	|	98766	|	4107	|	24.05	|	6620	|	6.70%	|	10872	|	11.01%	|	1073	|	1.09%	|	22	|	0.02%	|	41179	|	41.69%	|	57	|	5.24
8	|	Abdomen and pelvis	|	183475	|	7677	|	23.90	|	8792	|	4.79%	|	18637	|	10.16%	|	1259	|	0.69%	|	52	|	0.03%	|	77565	|	42.28%	|	56	|	5.21
9	|	Pelvic girdle and lower limb	|	114778	|	5097	|	22.52	|	5425	|	4.73%	|	9328	|	8.13%	|	555	|	0.48%	|	20	|	0.02%	|	49159	|	42.83%	|	54	|	5.22

> Table 2: The 9 sections of the book.

### Word clouds

Word clouds were constructed for each section for an overview of the most unique words for each section (using TF-IDF).
Though the results are not surprising and makes sense for the section titles, it is still interesting that there again are 9 sections compared to the 9 systems and 9 communities.
And again, these word clouds are very different from those of the anatomical systems and communities, meaning that the book is structured differently than these.

![](/images/section_1.png)  |  ![](/images/section_2.png)
:-------------------------:|:-------------------------:
Figure 1: Word cloud of section 1 - Cells, tissues and systems. | Figure 2: Word cloud of section 2 - Embryogenesis.

<br>

![](/images/section_3.png)  |  ![](/images/section_4.png)
:-------------------------:|:-------------------------:
Figure 3: Word cloud of section 3 - Neuroanatomy. | Figure 4: Word cloud of section 4 - Head and neck.

<br>

![](/images/section_5.png)  |  ![](/images/section_6.png)
:-------------------------:|:-------------------------:
Figure 5: Word cloud of section 5 - Back. | Figure 6: Word cloud of section 6 - Pectoral girdle and upper limb.

<br>

![](/images/section_7.png)  |  ![](/images/section_8.png)
:-------------------------:|:-------------------------:
Figure 7: Word cloud of section 7 - Thorax. | Figure 8: Word cloud of section 8 - Abdomen and pelvis.

<br>

![](/images/section_9.png) | <img width=500/>
:-------------------------:|:-------------------------:
Figure 9: Word cloud of section 9 - Pelvic girdle and lower limb. | <img width=1130/>


## Chapters

The chapters were also analysed individually, but yielded no interesting or deviating results, and the numbers are all quite close to those already seen in the entire book and sections.

The 10 most common words of each chapter is listed at the bottom of the page.

### Results

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
1	|	Basic structure and function of cells	|	20374	|	948	|	21.49	|	3388	|	16.63%	|	2704	|	13.27%	|	189	|	0.93%	|	33	|	0.16%	|	8017	|	39.35%	|	61	|	5.29
2	|	Integrating cells into tissues	|	11687	|	501	|	23.33	|	2349	|	20.10%	|	1520	|	13.01%	|	99	|	0.85%	|	8	|	0.07%	|	4676	|	40.01%	|	60	|	5.29
3	|	Nervous system	|	20511	|	924	|	22.20	|	3261	|	15.90%	|	2665	|	12.99%	|	233	|	1.14%	|	9	|	0.04%	|	8176	|	39.86%	|	59	|	5.30
4	|	Blood, lymphoid tissues and haemopoiesis	|	11897	|	2325	|	21.63	|	2325	|	19.54%	|	1573	|	13.22%	|	124	|	1.04%	|	3	|	0.03%	|	4758	|	39.99%	|	57	|	5.27
5	|	Functional anatomy of the musculoskeletal system	|	32437	|	1449	|	22.39	|	4512	|	13.91%	|	3763	|	11.60%	|	210	|	0.65%	|	7	|	0.02%	|	13258	|	40.87%	|	58	|	5.30
6	|	Smooth muscle and the cardiovascular and lymphatic systems	|	15078	|	692	|	21.79	|	2593	|	17.20%	|	1970	|	13.07%	|	130	|	0.86%	|	5	|	0.03%	|	6170	|	40.92%	|	57	|	5.31
7	|	Skin and its appendages	|	17862	|	816	|	21.89	|	3098	|	17.34%	|	1996	|	11.17%	|	156	|	0.87%	|	13	|	0.07%	|	7371	|	41.27%	|	54	|	5.28

Table 3: Text analysis of the chapters in Section 1: Cells, tissues and systems.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
8	|	Preimplantation development	|	5128	|	205	|	25.01	|	1389	|	27.09%	|	654	|	12.75%	|	33	|	0.64%	|	2	|	0.04%	|	2229	|	43.47%	|	59	|	5.28
9	|	Implantation and placentation	|	8345	|	354	|	23.57	|	1939	|	23.24%	|	1045	|	12.52%	|	116	|	1.39%	|	7	|	0.08%	|	3423	|	41.02%	|	60	|	5.26
10	|	Cell populations at gastrulation	|	6115	|	238	|	25.69	|	1195	|	19.54%	|	709	|	11.59%	|	52	|	0.85%	|	7	|	0.11%	|	2585	|	42.27%	|	59	|	5.26
11	|	Embryonic induction and cell division	|	2802	|	105	|	26.69	|	899	|	32.08%	|	453	|	16.17%	|	29	|	1.03%	|	3	|	0.11%	|	1144	|	40.83%	|	65	|	5.35
12	|	Cell populations at the start of organogenesis	|	4228	|	182	|	23.23	|	1007	|	23.82%	|	625	|	14.78%	|	43	|	1.02%	|	3	|	0.07%	|	1796	|	42.48%	|	57	|	5.29
13	|	Early embryonic circulation	|	3898	|	152	|	25.64	|	1011	|	25.94%	|	475	|	12.19%	|	30	|	0.77%	|	5	|	0.13%	|	1637	|	42.00%	|	59	|	5.27
14	|	Pre- and postnatal development	|	5942	|	237	|	25.07	|	1537	|	25.87%	|	582	|	9.79%	|	25	|	0.42%	|	3	|	0.05%	|	2522	|	42.44%	|	56	|	5.37
15	|	Development of the limbs	|	5088	|	196	|	25.96	|	1264	|	24.84%	|	608	|	11.95%	|	28	|	0.55%	|	0	|	0.00%	|	2087	|	41.02%	|	58	|	5.31

Table 4: Text analysis of the chapters in Section 2: Embryogenesis.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
16	|	Overview of the nervous system	|	7918	|	336	|	23.57	|	1618	|	20.43%	|	872	|	11.01%	|	83	|	1.05%	|	1	|	0.01%	|	3190	|	40.29%	|	59	|	5.25
17	|	Development of the nervous system	|	28786	|	1154	|	24.94	|	3716	|	12.91%	|	3295	|	11.45%	|	277	|	0.96%	|	6	|	0.02%	|	12079	|	41.96%	|	58	|	5.27
18	|	Ventricular system and subarachnoid space	|	5659	|	236	|	23.98	|	1206	|	21.31%	|	566	|	10.00%	|	56	|	0.99%	|	0	|	0.00%	|	2498	|	44.14%	|	57	|	5.19
19	|	Vascular supply and drainage of the brain	|	7216	|	299	|	24.13	|	1231	|	17.06%	|	590	|	8.18%	|	48	|	0.67%	|	0	|	0.00%	|	2933	|	40.65%	|	59	|	5.22
20	|	Spinal cord: internal organization	|	11535	|	530	|	21.76	|	1758	|	15.24%	|	1370	|	11.88%	|	117	|	1.01%	|	7	|	0.06%	|	4483	|	38.86%	|	56	|	5.25
21	|	Brainstem	|	18536	|	836	|	22.17	|	2299	|	12.40%	|	2239	|	12.08%	|	190	|	1.03%	|	5	|	0.03%	|	7461	|	40.25%	|	60	|	5.22
22	|	Cerebellum	|	8817	|	398	|	22.15	|	1458	|	16.54%	|	1150	|	13.04%	|	92	|	1.04%	|	4	|	0.05%	|	3694	|	41.90%	|	58	|	5.27
23	|	Diencephalon	|	11355	|	561	|	20.24	|	1954	|	17.21%	|	1564	|	13.77%	|	189	|	1.66%	|	21	|	0.18%	|	4480	|	39.45%	|	60	|	5.24
24	|	Basal ganglia	|	5361	|	236	|	22.72	|	1274	|	23.76%	|	725	|	13.52%	|	59	|	1.10%	|	4	|	0.07%	|	2238	|	41.75%	|	64	|	5.21
25	|	Cerebral hemispheres	|	21858	|	913	|	23.94	|	2487	|	11.38%	|	2687	|	12.29%	|	236	|	1.08%	|	9	|	0.04%	|	8766	|	40.10%	|	60	|	5.25

Table 5: Text analysis of the chapters in Section 3: Neuroanatomy.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
26	|	Head and neck: overview and surface anatomy	|	8243	|	330	|	24.98	|	1498	|	18.17%	|	669	|	8.12%	|	98	|	1.19%	|	0	|	0.00%	|	3566	|	43.26%	|	56	|	5.20
27	|	External skull	|	10353	|	430	|	24.08	|	1811	|	17.49%	|	954	|	9.21%	|	93	|	0.90%	|	0	|	0.00%	|	4571	|	44.15%	|	56	|	5.25
28	|	Intracranial region	|	11017	|	421	|	26.17	|	1566	|	14.21%	|	845	|	7.67%	|	60	|	0.54%	|	0	|	0.00%	|	4648	|	42.19%	|	60	|	5.18
29	|	Neck	|	32128	|	1375	|	23.37	|	2730	|	8.50%	|	2662	|	8.29%	|	326	|	1.01%	|	2	|	0.01%	|	13547	|	42.17%	|	56	|	5.20
30	|	Face and scalp	|	26915	|	1205	|	22.34	|	2791	|	10.37%	|	2345	|	8.71%	|	238	|	0.88%	|	1	|	0.00%	|	11503	|	42.74%	|	54	|	5.21
31	|	Oral cavity	|	19657	|	885	|	22.21	|	2665	|	13.56%	|	1832	|	9.32%	|	120	|	0.61%	|	1	|	0.01%	|	8414	|	42.80%	|	53	|	5.23
32	|	Infratemporal and pterygopalatine fossae and temporomandibular joint	|	19045	|	798	|	23.87	|	2221	|	11.66%	|	1678	|	8.81%	|	235	|	1.23%	|	0	|	0.00%	|	8221	|	43.17%	|	56	|	5.21
33	|	Nose, nasal cavity and paranasal sinuses	|	11177	|	462	|	24.19	|	1906	|	17.05%	|	991	|	8.87%	|	76	|	0.68%	|	0	|	0.00%	|	4756	|	42.55%	|	55	|	5.20
34	|	Pharynx	|	13608	|	521	|	26.12	|	2157	|	15.85%	|	1616	|	11.88%	|	235	|	1.73%	|	5	|	0.04%	|	5969	|	43.86%	|	58	|	5.23
35	|	Larynx	|	18015	|	753	|	23.92	|	2593	|	14.39%	|	1634	|	9.07%	|	101	|	0.56%	|	4	|	0.02%	|	8162	|	45.31%	|	56	|	5.24
36	|	Development of the head and neck	|	14066	|	560	|	25.12	|	2238	|	15.91%	|	1600	|	11.37%	|	129	|	0.92%	|	7	|	0.05%	|	5979	|	42.51%	|	56	|	5.25
37	|	External and middle ear	|	15235	|	673	|	22.64	|	2179	|	14.30%	|	1112	|	7.30%	|	119	|	0.78%	|	0	|	0.00%	|	6776	|	44.48%	|	54	|	5.19
38	|	Inner ear	|	13290	|	540	|	24.61	|	2128	|	16.01%	|	1214	|	9.13%	|	77	|	0.58%	|	0	|	0.00%	|	5727	|	43.09%	|	57	|	5.25
39	|	Development of the ear	|	2381	|	90	|	26.46	|	741	|	31.12%	|	279	|	11.72%	|	20	|	0.84%	|	0	|	0.00%	|	1002	|	42.08%	|	59	|	5.25
40	|	Development of the eye	|	4425	|	164	|	26.98	|	1147	|	25.92%	|	499	|	11.28%	|	38	|	0.86%	|	2	|	0.05%	|	1866	|	42.17%	|	59	|	5.28
41	|	Orbit and accessory visual apparatus	|	16769	|	710	|	23.62	|	2239	|	13.35%	|	1430	|	8.53%	|	87	|	0.52%	|	1	|	0.01%	|	7114	|	42.42%	|	56	|	5.23
42	|	Eye	|	15539	|	653	|	23.80	|	2477	|	15.94%	|	1467	|	9.44%	|	73	|	0.47%	|	0	|	0.00%	|	6485	|	41.73%	|	56	|	5.27

Table 6: Text analysis of the chapters in Section 4: Head and neck.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
43	|	Back	|	32139	|	1479	|	21.73	|	3075	|	9.57%	|	2742	|	8.53%	|	206	|	0.64%	|	2	|	0.01%	|	13656	|	42.49%	|	55	|	5.24
44	|	Development of the back	|	6311	|	286	|	22.07	|	1374	|	21.77%	|	735	|	11.65%	|	46	|	0.73%	|	1	|	0.02%	|	2672	|	42.34%	|	55	|	5.28
45	|	Spinal cord and spinal nerves: gross anatomy	|	9647	|	400	|	24.12	|	1589	|	16.47%	|	731	|	7.58%	|	40	|	0.41%	|	0	|	0.00%	|	3956	|	41.01%	|	53	|	5.20

Table 7: Text analysis of the chapters in Section 5: Back.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
46	|	Pectoral girdle and upper limb: overview and surface anatomy	|	12413	|	528	|	23.51	|	1593	|	12.83%	|	926	|	7.46%	|	88	|	0.71%	|	1	|	0.01%	|	5402	|	43.52%	|	52	|	5.22
47	|	Development of the pectoral girdle and upper limb	|	2435	|	104	|	23.41	|	790	|	32.44%	|	242	|	9.94%	|	11	|	0.45%	|	0	|	0.00%	|	1048	|	43.04%	|	53	|	5.27
48	|	Shoulder girdle and arm	|	31967	|	1320	|	24.22	|	2473	|	7.74%	|	2821	|	8.82%	|	382	|	1.19%	|	7	|	0.02%	|	14042	|	43.93%	|	56	|	5.21
49	|	Elbow and forearm	|	18609	|	872	|	21.34	|	1490	|	8.01%	|	1417	|	7.61%	|	88	|	0.47%	|	0	|	0.00%	|	7901	|	42.46%	|	52	|	5.20
50	|	Wrist and hand	|	23364	|	1066	|	21.92	|	2093	|	8.96%	|	1920	|	8.22%	|	213	|	0.91%	|	6	|	0.03%	|	9939	|	42.54%	|	51	|	5.24

Table 8: Text analysis of the chapters in Section 6: Pectoral girdle and upper limb.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
51	|	Thorax: overview and surface anatomy	|	5628	|	203	|	27.72	|	1045	|	18.57%	|	502	|	8.92%	|	43	|	0.76%	|	0	|	0.00%	|	2373	|	42.16%	|	58	|	5.21
52	|	Development of the thorax	|	23394	|	944	|	24.78	|	3192	|	13.64%	|	2961	|	12.66%	|	291	|	1.24%	|	10	|	0.04%	|	9980	|	42.66%	|	58	|	5.28
53	|	Chest wall and breast	|	16474	|	758	|	21.73	|	2168	|	13.16%	|	1621	|	9.84%	|	133	|	0.81%	|	1	|	0.01%	|	6831	|	41.47%	|	54	|	5.24
54	|	Pleura, lungs, trachea and bronchi	|	11848	|	486	|	24.38	|	2079	|	17.55%	|	1201	|	10.14%	|	93	|	0.78%	|	1	|	0.01%	|	4888	|	41.26%	|	59	|	5.22
55	|	Diaphragm and phrenic nerves	|	5080	|	211	|	24.08	|	1142	|	22.48%	|	480	|	9.45%	|	46	|	0.91%	|	1	|	0.02%	|	2193	|	43.17%	|	55	|	5.22
56	|	Mediastinum	|	10876	|	449	|	24.22	|	2077	|	19.10%	|	1406	|	12.93%	|	140	|	1.29%	|	3	|	0.03%	|	4407	|	40.52%	|	59	|	5.21
57	|	Heart	|	20555	|	839	|	24.50	|	2551	|	12.41%	|	2187	|	10.64%	|	253	|	1.23%	|	4	|	0.02%	|	8557	|	41.63%	|	58	|	5.24
58	|	Great vessels	|	4911	|	217	|	22.63	|	1013	|	20.63%	|	514	|	10.47%	|	74	|	1.51%	|	2	|	0.04%	|	1950	|	39.71%	|	55	|	5.21

Table 9: Text analysis of the chapters in Section 7: Thorax.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
59	|	Abdomen and pelvis: overview and surface anatomy	|	10842	|	425	|	25.51	|	1852	|	17.08%	|	1109	|	10.23%	|	85	|	0.78%	|	0	|	0.00%	|	4507	|	41.57%	|	58	|	5.21
60	|	Development of the peritoneal cavity, gastrointestinal tract and its adnexae	|	19640	|	847	|	23.19	|	2715	|	13.82%	|	2274	|	11.58%	|	172	|	0.88%	|	18	|	0.09%	|	8476	|	43.16%	|	56	|	5.23
61	|	Anterior abdominal wall	|	8599	|	375	|	22.93	|	1354	|	15.75%	|	782	|	9.09%	|	34	|	0.40%	|	0	|	0.00%	|	3642	|	42.35%	|	56	|	5.21
62	|	Posterior abdominal wall and retroperitoneum	|	9922	|	408	|	24.32	|	1416	|	14.27%	|	880	|	8.87%	|	86	|	0.87%	|	3	|	0.03%	|	4041	|	40.73%	|	55	|	5.18
63	|	Peritoneum and peritoneal cavity	|	10823	|	445	|	24.32	|	1526	|	14.10%	|	1166	|	10.77%	|	39	|	0.36%	|	1	|	0.01%	|	4782	|	44.18%	|	57	|	5.16
64	|	Abdominal oesophagus and stomach	|	8068	|	321	|	25.13	|	1523	|	18.88%	|	834	|	10.34%	|	79	|	0.98%	|	2	|	0.02%	|	3357	|	41.61%	|	60	|	5.21
65	|	Small intestine	|	7975	|	331	|	24.09	|	1517	|	19.02%	|	842	|	10.56%	|	78	|	0.98%	|	1	|	0.01%	|	3329	|	41.74%	|	57	|	5.22
66	|	Large intestine	|	13139	|	505	|	26.02	|	1959	|	14.91%	|	1339	|	10.19%	|	79	|	0.60%	|	0	|	0.00%	|	5446	|	41.45%	|	58	|	5.20
67	|	Liver	|	9312	|	377	|	24.70	|	1555	|	16.70%	|	778	|	8.35%	|	33	|	0.35%	|	1	|	0.01%	|	3890	|	41.77%	|	55	|	5.18
68	|	Gallbladder and biliary tree	|	4101	|	155	|	26.46	|	909	|	22.17%	|	386	|	9.41%	|	25	|	0.61%	|	3	|	0.07%	|	1747	|	42.60%	|	55	|	5.19
69	|	Pancreas	|	4175	|	172	|	24.27	|	888	|	21.27%	|	441	|	10.56%	|	69	|	1.65%	|	3	|	0.07%	|	1734	|	41.53%	|	57	|	5.19
70	|	Spleen	|	3874	|	149	|	26.00	|	1004	|	25.92%	|	393	|	10.14%	|	25	|	0.65%	|	0	|	0.00%	|	1660	|	42.85%	|	58	|	5.16
71	|	Suprarenal (adrenal) gland	|	2899	|	128	|	22.65	|	882	|	30.42%	|	326	|	11.25%	|	20	|	0.69%	|	3	|	0.10%	|	1176	|	40.57%	|	55	|	5.19
72	|	Development of the urogenital system	|	14226	|	626	|	22.73	|	2413	|	16.96%	|	1640	|	11.53%	|	89	|	0.63%	|	5	|	0.04%	|	6237	|	43.84%	|	55	|	5.25
73	|	True pelvis, pelvic floor and perineum	|	13533	|	543	|	24.92	|	1533	|	11.33%	|	1085	|	8.02%	|	79	|	0.58%	|	0	|	0.00%	|	5807	|	42.91%	|	55	|	5.20
74	|	Kidney and ureter	|	10544	|	441	|	23.91	|	2010	|	19.06%	|	1049	|	9.95%	|	70	|	0.66%	|	2	|	0.02%	|	4413	|	41.85%	|	56	|	5.20
75	|	Bladder, prostate and urethra	|	9639	|	411	|	23.45	|	1764	|	18.30%	|	999	|	10.36%	|	79	|	0.82%	|	4	|	0.04%	|	4022	|	41.73%	|	58	|	5.23
76	|	Male reproductive system	|	8328	|	377	|	22.09	|	1691	|	20.30%	|	1006	|	12.08%	|	59	|	0.71%	|	0	|	0.00%	|	3362	|	40.37%	|	56	|	5.24
77	|	Female reproductive system	|	13836	|	641	|	21.59	|	2299	|	16.62%	|	1308	|	9.45%	|	59	|	0.43%	|	6	|	0.04%	|	5937	|	42.91%	|	54	|	5.25

Table 10: Text analysis of the chapters in Section 8: Abdomen and pelvis.

Chapter	|	Name	|	Words	|	Sentences	|	Words pr. sentence	|	Unique words	|	% of text	|	Long words (10+)	|	% of text	|	Long words (15+)	|	% of text	|	Long words (20+)	|	% of text	|	Stopwords	|	% of text	|	Lix score	|	Sentiment score
---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---	|	---
78	|	Pelvic girdle and lower limb: overview and surface anatomy	|	12123	|	494	|	24.54	|	1817	|	14.99%	|	920	|	7.59%	|	41	|	0.34%	|	0	|	0.00%	|	5316	|	43.85%	|	54	|	5.20
79	|	Development of the pelvic girdle and lower limb	|	2677	|	117	|	22.88	|	910	|	33.99%	|	261	|	9.75%	|	8	|	0.30%	|	1	|	0.04%	|	1178	|	44.00%	|	53	|	5.26
80	|	Pelvic girdle, gluteal region and thigh	|	36840	|	1694	|	21.75	|	2819	|	7.65%	|	2855	|	7.75%	|	151	|	0.41%	|	1	|	0.00%	|	15822	|	42.95%	|	53	|	5.21
81	|	Hip	|	4043	|	172	|	23.51	|	1027	|	25.40%	|	400	|	9.89%	|	24	|	0.59%	|	0	|	0.00%	|	1725	|	42.67%	|	57	|	5.25
82	|	Knee	|	14207	|	639	|	22.23	|	1975	|	13.90%	|	1191	|	8.38%	|	72	|	0.51%	|	0	|	0.00%	|	6144	|	43.25%	|	57	|	5.21
83	|	Leg	|	16058	|	709	|	22.65	|	1652	|	10.29%	|	1178	|	7.34%	|	54	|	0.34%	|	2	|	0.01%	|	6843	|	42.61%	|	54	|	5.21
84	|	Ankle and foot	|	28830	|	1272	|	22.67	|	2505	|	8.69%	|	2523	|	8.75%	|	205	|	0.71%	|	16	|	0.06%	|	12131	|	42.08%	|	55	|	5.22

Table 11: Text analysis of the chapters in Section 9: Pelvic girdle and lower limb.

### Most common words

Below, the 10 most common words (in order after number of mentions) can be found.

Chapter 1: cell, cells, proteins, membrane, protein, form, filaments, plasma, see, molecules

Chapter 2: cells, tissue, tissues, connective, cell, glands, epithelium, e.g., matrix, form

Chapter 3: cells, neurones, fibres, axons, cns, muscle, axon, cell, endings, myelin

Chapter 4: cells, lymphocytes, blood, macrophages, marrow, b, cell, lymphoid, dendritic, tissues

Chapter 5: bone, muscle, cartilage, fibres, cells, collagen, muscles, growth, bones, joints

Chapter 6: muscle, cells, smooth, blood, vessels, arteries, cardiac, cell, endothelial, veins

Chapter 7: cells, skin, layer, hair, nail, epidermis, dermis, matrix, surface, lines

Chapter 8: cells, cell, embryos, hypoblast, embryo, trophoblast, development, extraembryonic, epiblast, blastocyst

Chapter 9: cells, maternal, fetal, amniotic, umbilical, placenta, trophoblast, blood, decidua, villi

Chapter 10: cells, streak, primitive, plate, neural, epiblast, embryonic, epithelial, cell, disc

Chapter 11: cells, cell, tissue, development, embryo, within, interactions, molecules, e.g., embryonic

Chapter 12: cells, mesenchyme, neural, crest, embryo, form, lateral, epithelium, ectoderm, mesenchymal

Chapter 13: veins, arteries, vessels, vein, early, dorsal, umbilical, embryo, lymph, form

Chapter 14: growth, birth, fetal, age, weeks, weight, period, length, development, delivery

Chapter 15: limb, bud, cells, development, ectodermal, ridge, apical, mesenchyme, axons, movements

Chapter 16: spinal, neurones, nerves, fibres, sympathetic, system, cranial, ganglia, cord, nervous

Chapter 17: cells, neural, neurones, lateral, crest, plate, part, form, cerebral, zone

Chapter 18: ventricle, lateral, space, fourth, csf, subarachnoid, choroid, inferior, plexus, cistern

Chapter 19: artery, cerebral, posterior, anterior, arteries, branches, supply, internal, lateral, blood

Chapter 20: neurones, fibres, spinal, tract, dorsal, cord, ventral, lateral, nucleus, lamina

Chapter 21: nucleus, fibres, nuclei, neurones, medial, nerve, lateral, spinal, ventral, dorsal

Chapter 22: nucleus, fibres, cerebellum, cerebellar, nuclei, cells, purkinje, zones, lobule, cortex

Chapter 23: nucleus, nuclei, lateral, posterior, medial, neurones, fibres, ventral, anterior, hypothalamus

Chapter 24: nucleus, striatum, subthalamic, internal, caudate, neurones, basal, pars, ventral, ganglia

Chapter 25: cortex, area, temporal, gyrus, areas, anterior, fibres, inferior, medial, lateral

Chapter 26: neck, cervical, anterior, posterior, border, nerve, palpable, cm, vein, branches

Chapter 27: bone, skull, bones, posterior, foramen, process, temporal, part, fossa, growth

Chapter 28: sinus, posterior, bone, cranial, superior, foramen, anterior, meningeal, veins, sinuses

Chapter 29: artery, cervical, anterior, nerve, carotid, posterior, thyroid, inferior, vein, branches

Chapter 30: nerve, bone, artery, surface, facial, part, nasal, anterior, lateral, posterior

Chapter 31: lingual, nerve, teeth, tongue, surface, gland, part, artery, alveolar, glands

Chapter 32: nerve, pterygoid, lateral, artery, anterior, mandibular, posterior, medial, fossa, part

Chapter 33: nasal, lateral, anterior, part, posterior, olfactory, sinus, sinuses, ethmoidal, cells

Chapter 34: pharyngeal, palate, part, artery, tonsil, posterior, palatine, soft, swallowing, pharynx

Chapter 35: vocal, laryngeal, larynx, folds, cartilage, thyroid, posterior, nerve, arytenoid, superior

Chapter 36: form, neural, arch, pharyngeal, part, mesenchyme, crest, cells, first, bone

Chapter 37: tympanic, part, posterior, bone, nerve, mastoid, anterior, membrane, process, cavity

Chapter 38: cells, hair, cochlear, vestibular, membrane, nerve, inner, spiral, outer, cell

Chapter 39: part, ear, cells, first, arch, tympanic, pharyngeal, second, cavity, inner

Chapter 40: optic, cells, lens, eye, neural, retina, epithelium, cup, anterior, layer

Chapter 41: nerve, superior, orbital, inferior, lateral, lacrimal, medial, orbit, artery, rectus

Chapter 42: cells, retina, layer, optic, ciliary, retinal, lens, nerve, anterior, fibres

Chapter 43: vertebral, posterior, lumbar, cervical, lateral, thoracic, anterior, transverse, muscles, vertebrae

Chapter 44: cells, vertebrae, processes, neural, somite, vertebral, form, development, sclerotome, dermomyotome

Chapter 45: spinal, dorsal, cord, roots, nerves, cervical, branches, nerve, ventral, vertebral

Chapter 46: nerve, lateral, deep, medial, artery, anterior, flexor, posterior, radial, muscles

Chapter 47: limb, upper, artery, hand, bud, stage, distal, ulnar, mesenchyme, arteries

Chapter 48: lateral, medial, artery, anterior, posterior, nerve, border, surface, joint, part

Chapter 49: extensor, radial, flexor, artery, ulnar, posterior, distal, interosseous, nerve, medial

Chapter 50: palmar, dorsal, flexor, metacarpal, distal, pollicis, ulnar, proximal, joint, digital

Chapter 51: thoracic, right, left, level, intercostal, costal, line, superior, vertebra, rib

Chapter 52: heart, left, right, development, cells, pulmonary, atrioventricular, septum, lung, atrial

Chapter 53: intercostal, thoracic, anterior, posterior, breast, costal, internal, first, branches, lateral

Chapter 54: pulmonary, left, lung, right, superior, pleura, inferior, bronchus, surface, anterior

Chapter 55: diaphragm, left, phrenic, right, nerve, inferior, fibres, superior, anterior, central

Chapter 56: thoracic, left, posterior, oesophagus, right, oesophageal, vein, superior, mediastinum, thymus

Chapter 57: left, right, cardiac, coronary, ventricular, artery, valve, atrial, anterior, ventricle

Chapter 58: left, right, artery, aorta, posterior, thoracic, arteries, pulmonary, aortic, superior

Chapter 59: plexus, superior, inferior, sympathetic, nerve, lumbar, nerves, anterior, abdominal, branches

Chapter 60: dorsal, ventral, right, left, gut, cells, mesenchyme, part, development, hepatic

Chapter 61: inguinal, anterior, abdominal, abdominis, fibres, oblique, ligament, rectus, wall, artery

Chapter 62: lumbar, inferior, posterior, right, anterior, left, abdominal, nerve, nodes, lateral

Chapter 63: peritoneum, peritoneal, left, right, posterior, abdominal, wall, ligament, anterior, omentum

Chapter 64: gastric, stomach, left, oesophagus, artery, lesser, posterior, pyloric, surface, right

Chapter 65: duodenum, artery, superior, cells, small, mesenteric, part, ileum, right, anterior

Chapter 66: colon, anal, artery, rectal, left, colic, rectum, inferior, sigmoid, mesenteric

Chapter 67: hepatic, liver, right, left, vein, portal, segment, inferior, lobe, artery

Chapter 68: duct, bile, gallbladder, hepatic, common, cystic, right, artery, ducts, usually

Chapter 69: artery, pancreatic, pancreas, superior, pancreaticoduodenal, anterior, posterior, gland, inferior, head

Chapter 70: splenic, spleen, left, petroianu, ligament, pulp, blood, artery, gastric, posterior

Chapter 71: suprarenal, gland, right, inferior, left, cells, vein, artery, arteries, cortex

Chapter 72: cells, development, mesonephric, mesenchyme, bladder, ducts, duct, urogenital, form, genital

Chapter 73: artery, iliac, perineal, pelvic, fascia, inferior, anterior, internal, posterior, sacral

Chapter 74: renal, ureter, cells, kidney, vessels, anterior, glomerular, pelvis, arteries, inferior

Chapter 75: urethra, bladder, muscle, urethral, prostate, prostatic, anterior, smooth, fibres, sphincter

Chapter 76: artery, testis, cells, penis, testicular, epididymis, tunica, spermatic, veins, penile

Chapter 77: uterine, uterus, cells, cervix, vessels, ovarian, ligament, vagina, pregnancy, tissue

Chapter 78: lateral, medial, anterior, nerve, posterior, foot, lower, limb, joint, knee

Chapter 79: limb, lower, development, hip, talus, birth, femur, vein, head, fetal

Chapter 80: femoral, artery, medial, surface, anterior, lateral, nerve, posterior, part, adductor

Chapter 81: hip, joint, femoral, ligament, acetabular, head, capsule, body, muscles, femur

Chapter 82: lateral, medial, knee, joint, posterior, tibial, ligament, anterior, femoral, popliteal

Chapter 83: anterior, lateral, posterior, medial, fibular, longus, tibial, artery, nerve, surface

Chapter 84: plantar, medial, lateral, metatarsal, flexor, joint, surface, tendon, ligament, foot

