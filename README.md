usage:  ./list.sh filename or dirname [column_num] ['keyword or regexp'] [isAlignCourseName]

filename or dirname: the course file or dir

column_num: from 1 to 3

keyword or regexp: the keyword for filter course

keyword suggest(to list keyword, please run ./list.sh help filename):

     1	 106 university
     2	  78 of
     3	  30 and
     4	  20 stanford
     5	  19 the
     6	  18 to
     7	  14 programming
     8	  14 at
     9	  13 introduction
    10	  12 urbana
    11	  12 illinois
    12	  12 champaign
    13	   9 washington
    14	   9 part
    15	   9 for
    16	   9 computer
    17	   9 cole
    18	   9 algorithms
    19	   8 princeton
    20	   8 in
    21	   7 security
    22	   7 rale
    23	   7 polytechnique
    24	   7 lausanne
    25	   7 f
    26	   7 de
    27	   7 data
    28	   7 d
    29	   7 california
    30	   7 analysis
    31	   6 technology
    32	   6 processing
    33	   6 park
    34	   6 networks
    35	   6 maryland
    36	   6 computing
    37	   6 college
    38	   5 systems
    39	   5 software
    40	   5 science
    41	   5 san
    42	   5 mining
    43	   5 institute
    44	   5 information
    45	   5 game
    46	   5 digital
    47	   5 diego
    48	   5 computational
    49	   5 cloud
    50	   5 c
    51	   4 rice
    52	   4 principles
    53	   4 new
    54	   4 mobile
    55	   4 michigan
    56	   4 logic
    57	   4 learning
    58	   4 language
    59	   4 georgia
    60	   4 design
    61	   4 columbia
    62	   4 applications
    63	   4 android
    64	   4 an
    65	   3 with
    66	   3 toronto
    67	   3 theory
    68	   3 state
    69	   3 programmation
    70	   3 program
    71	   3 melbourne
    72	   3 machine
    73	   3 london
    74	   3 la
    75	   3 interactive
    76	   3 ii
    77	   3 i
    78	   3 handheld
    79	   3 fundamentals
    80	   3 en
    81	   3 edinburgh
    82	   3 discrete
    83	   3 cryptography
    84	   3 british
    85	   3 bioinformatics
    86	   3 arts
    87	   2 york
    88	   2 web
    89	   2 video
    90	   2 vanderbilt
    91	   2 tokyo
    92	   2 text
    93	   2 social
    94	   2 services
    95	   2 school
    96	   2 risk
    97	   2 python
    98	   2 pennsylvania
    99	   2 pattern
   100	   2 optimization
   101	   2 neuroscience
   102	   2 networking
   103	   2 network
   104	   2 natural
   105	   2 models
   106	   2 minnesota
   107	   2 mexico
   108	   2 management
   109	   2 linear
   110	   2 learn
   111	   2 johns
   112	   2 internet
   113	   2 interaction
   114	   2 intelligence
   115	   2 initiation
   116	   2 image
   117	   2 human
   118	   2 hopkins
   119	   2 hardware
   120	   2 graphics
   121	   2 from
   122	   2 creative
   123	   2 concepts
   124	   2 code
   125	   2 biology
   126	   2 artificial
   127	   2 architectures
   128	   2 apps
   129	   1 yourself
   130	   1 your
   131	   1 without
   132	   1 will
   133	   1 welcome
   134	   1 webgl
   135	   1 voting
   136	   1 vlsi
   137	   1 visualization
   138	   1 vision
   139	   1 usable
   140	   1 unpredictable
   141	   1 underground
   142	   1 two
   143	   1 toolkit
   144	   1 through
   145	   1 thinking
   146	   1 things
   147	   1 systematic
   148	   1 system
   149	   1 surveillance
   150	   1 sup
   151	   1 strategies
   152	   1 story
   153	   1 stop
   154	   1 statistical
   155	   1 startup
   156	   1 spatial
   157	   1 skills
   158	   1 singapore
   159	   1 sinai
   160	   1 signal
   161	   1 sides
   162	   1 serious
   163	   1 securing
   164	   1 search
   165	   1 sciences
   166	   1 scala
   167	   1 santa
   168	   1 robots
   169	   1 rieure
   170	   1 retrieval
   171	   1 recommender
   172	   1 reactive
   173	   1 randomness
   174	   1 quality
   175	   1 programmers
   176	   1 products
   177	   1 process
   178	   1 probabilistic
   179	   1 playing
   180	   1 playful
   181	   1 planning
   182	   1 photography
   183	   1 philosophy
   184	   1 peking
   185	   1 paris
   186	   1 parallel
   187	   1 oriented
   188	   1 orient
   189	   1 objet
   190	   1 northwestern
   191	   1 normale
   192	   1 none
   193	   1 neuromarketing
   194	   1 neural
   195	   1 networked
   196	   1 national
   197	   1 musicians
   198	   1 mount
   199	   1 money
   200	   1 methods
   201	   1 medicine
   202	   1 media
   203	   1 mechanics
   204	   1 matrix
   205	   1 massive
   206	   1 mars
   207	   1 maps
   208	   1 malicious
   209	   1 making
   210	   1 life
   211	   1 layout
   212	   1 law
   213	   1 languages
   214	   1 judgement
   215	   1 java
   216	   1 its
   217	   1 investing
   218	   1 interface
   219	   1 innovation
   220	   1 inference
   221	   1 illustrated
   222	   1 icahn
   223	   1 hospital
   224	   1 hollywood
   225	   1 history
   226	   1 heterogeneous
   227	   1 group
   228	   1 graphical
   229	   1 gps
   230	   1 google
   231	   1 general
   232	   1 functional
   233	   1 friends
   234	   1 free
   235	   1 fog
   236	   1 fair
   237	   1 executing
   238	   1 exam
   239	   1 everybody
   240	   1 every
   241	   1 enhance
   242	   1 engines
   243	   1 engineering
   244	   1 employability
   245	   1 eindhoven
   246	   1 economy
   247	   1 economic
   248	   1 e
   249	   1 duke
   250	   1 division
   251	   1 discovery
   252	   1 developing
   253	   1 designing
   254	   1 democracy
   255	   1 defined
   256	   1 decisions
   257	   1 datasets
   258	   1 databases
   259	   1 cruz
   260	   1 creativity
   261	   1 crafting
   262	   1 copenhagen
   263	   1 control
   264	   1 context
   265	   1 consumer
   266	   1 computations
   267	   1 compilers
   268	   1 combinatorics
   269	   1 colorado
   270	   1 coding
   271	   1 cluster
   272	   1 change
   273	   1 chance
   274	   1 centrale
   275	   1 career
   276	   1 capstone
   277	   1 calculus
   278	   1 cad
   279	   1 bytes
   280	   1 business
   281	   1 building
   282	   1 brown
   283	   1 big
   284	   1 better
   285	   1 beginning
   286	   1 beginners
   287	   1 automata
   288	   1 artists
   289	   1 architecture
   290	   1 application
   291	   1 analytics
   292	   1 analytic
   293	   1 algorithmic
   294	   1 algebra
   295	   1 aggregation
   296	   1 advanced
   297	   1 action
   298	   1 a
eg: ./list.sh db/eecs-course-all2014 2 'Machine learning'

    ./list.sh db/eecs-course-all2014 1 '^cs.*Cryptography'

    ./list.sh db/eecs/eecs-course-edx2014 2 '' no | sort  -k1 -n -r
===========