# Codebuch Hitler Finanzierungsströme #
Codebuch Stand 2021- Juni  
erstellt von Anina Kemmerling, Chiara Maier, Julia Habenicht, Paulina Blech

## Inhalt
- Edges.csv (Edgelist)
- Nodes.csv (Nodelist)
- Codebuch.md (Codierung der Datensätze)

# EDGE-Attribute

**id**  
(eindeutige Codierung des Knoten)   

**weight**   
Stärke der Unterstützung   
3 = starke Unterstützung,  
2 = mäßige Unterstützung,  
1 = schwache Unterstützung.

**time**  
Zeitraum, in dem der Geldfluss zwischen zwei Knoten stattgefunden hat.

**use**  
Hitlers Verwendungszweck des Geldes

# NODE-Attribute  
  
**id**  
Identische ID wie aus der edgelist zur Identifikation der Knoten. 

**name**  
Name oder Bezeichnung des Knotens.

**sex**    
dichotome Ausprägung  
1 = männlich,  
2 = weiblich,  
3 = divers.
  
**work**    
definiert, aus welcher Branche der Knoten kommt.  
1 = Politik,  
2 = Wirtschaft.

**type**   
definiert, um welche Art von Knoten es sich handelt.  
1 = Person,   
2 = Organisation.    

**money**    
definiert die Geldbeträge.  
1 = 0-10 Tsd.,  
2 = 10-20 Tsd.,  
3 = 20-50 Tsd.,  
4 = 50-100 Tsd.,  
5 = 100 Tsd.<.
  
**moneytype**  
definiert die Art des Geldflusses.  
1 = Darlehen,       
2 = Kredit,    
3 = Spende.    
  
**timeframe**    
definiert die Häufigkeit des Geldflusses.  
1 = einmalig,   
2 = regelmäßig.   

**country**  
Herkunftsland des/der Geldgeber*in  
1 = Schweiz,      
2 = Amerika,   
3 = Deutschland,    
4 = Österreich,  
5 = England,  
6 = Russland,  
7 = sonstige.

##
