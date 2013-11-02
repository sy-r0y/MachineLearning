Week 1 Lecture 1

- Machine Learning grew out of Artificial Intelligence.
- Provides new capabilities to the computers.

Exmp
     - 1. Database Mining.
       	   Large dataset from growth of automation/web.

     - 2. Natural Language Processing.
           Siri, Summly

     - 3. Self customization programs.
           Amazof/Netflix recommender systems


Definition of ML:-
- Arthur Samuel(1959): Machine learning is the field of study that gives computers the ability ot learn without explicitly programmed.

- Tom Mitchell(1998): A computer program is said to learn from experience(E) with respect to some task(T) and some performance measure(P), if its performace on T, as measured byu P, improves with experience(E).

Exmpl- Gmail wathces me mark some emails as Spam and some as not & based on that learns & better filters my emails as spam or not.

Two types of ML Algos: 
    	     	       1. Supervised Learning.
		       2. Unsupervised Learning.

Other types: Reinforcement learning, recommender systems.

----------------------------------------------------

Supervised Learning expl - 

1. Housing price prediction from previously available data.

      Regression: Predict continous valued output(price)

2. Brease cancer (either malignant or benign)
      Classification: Discrete valued output(either 0 or 1)

Example: 

- Regression Problem: Factory has inventory of identical items. Predict how many items will sell over next 3 months.		
- Discrete problem: Email software, examines individual customer accounts & for each customer account decides if it has been hacked/compromised.


Unsupervised learning expl (CLUSTERING)- 


  -   Google News: every day google crawler goes through thousands of news articles, the crawler finds patterns in many aricles similar to other articles. then its ml algo decides to create a CLUSTER of such similar article.
  
  -  Genome project: create genome sequence of millions of humans. Find similar pattern between such different individuals then cluster these into various "segments".

  - Market Segments: Algo finds patterns between thousands of customers of businesss. Finds a similar pattern between several people. creates "segments" of such persons. Marketing can be targeted at various segments.

  - Social network analysis.

  - Coctail party problem: too much noise in party, algo tries to find pattern & seperates the sound noise into inputs. 

Simple to code the cocktail party problem in Octave

[W,s,v] = svd((repmat(sum(x.*x,1),size(x,1),1).*x)*x1);

	svd -> Singular value decomposition.