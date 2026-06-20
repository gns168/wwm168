---
title: AvenueXtra Guild
GameID: "10157338"
Leader: "[[avenuex 顾明]]"
External:
  - https://discord.gg/HE6P7NMqY
Ext Description: Discord for AvenueXtra Guild
img: "[[guild.png]]"
---
![[banner.png]] 


```mermaid
graph TB

%% Structure
l((avenuex 顾明))
g(AvenueXtra)
c1(_Dramallama Cohort)
c2(_Enchanted Cohort)
c3(_Not Lonely Cohort)
m(Members)
e[external]

%% Members

m1((gnsyiliuba))
m2((gns))
m3((tierce))
m4((wuchang))
m5((baoyu 宝玉))
m6((nhatthao))
m7((faeonix))
m8((hekapider))
m9((dongfunbubai))

%% Relationship

l --> |Leader| g
m2 --> |Partnership| m1
m2 --> |Eldest| m1

subgraph Guild
	g ---> |Groups| Cohorts & m
	m
	subgraph Cohorts
		l --> |Elder| c1
			c1 --> |2nd| m2
				m2 --> |2nd| m8
				m2 --> |3rd| m9
		m1 --> |Elder| c2
			m1 --> |Eldest| m4
			m1 --> |2nd| m5
			m1 --> |3rd| m6
			m1 --> |4th| m7
		c3
	end
	m2 -.- |Former Partnership| m3
end





class g,c1,c2,c3,m,e internal-link
class l,m1,m2,m3,m4,m5,m6,m7,m8,m9 internal-link
```

---

# [[Cohorts]]
# [[Members]]
# [[GVG]]
