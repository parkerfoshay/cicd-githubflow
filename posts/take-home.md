---
title: 'Aggregation?'
date: '2020-01-09'
---

# 🔘 Explain The Pipeline

## ❗ Instructions

Take time to add comments describing the functionality of the code found in the [query.sh](./Unsolved/query.sh) file.

**Important**: This activity uses the sample dataset that is available on [Atlas](https://docs.atlas.mongodb.com/sample-data/).

## 🚀 Launch The Demo

To launch the application, follow these steps:

1. In the command line, run `mongo "mongodb+srv://<your username>:<your password>@<your cluster>.uzpoq.mongodb.net/admin" --username <your username>`.

2. Once connected, type `use sample_restaurants` into the command line.

3. Once connected to the `sample_restaurants` database copy and paste the query into the command line.

## 🎂 Expected Results

```sh
{ "_id" : "Five Star Fish & Chips", "avgScore" : 31 }
{ "_id" : "Lucky 13 Saloon", "avgScore" : 31.833333333333332 }
{ "_id" : "The Manhattan Inn", "avgScore" : 40 }
{ "_id" : "Zamba Rios", "avgScore" : 37 }
{ "_id" : "Crown Chicken Pizza & Coffee Shop", "avgScore" : 41 }
```


Refer to the documentation: 

* [MongoDB Documentation On Aggregation](https://docs.mongodb.com/manual/aggregation/)

* [MongoDB Documentation On $unwind](https://docs.mongodb.com/manual/reference/operator/aggregation/unwind/)

---

## 💹 Knowledge Boost

If you have completed this activity, work through the following challenge with your partner to further your knowledge:

* Which MongoDB tool can help you construct your own aggregation pipeline?

Use [Google](https://www.google.com) or another search engine to research this.

---