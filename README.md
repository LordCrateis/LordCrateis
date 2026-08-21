<!--
    github.com/LordCrateis

    Not a résumé.
    Not a dashboard.
    More like an open engineering log.
-->

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0D1117,55:171022,100:6F00FF&height=6&section=header" width="100%"/>

<div align="center">

<pre>
██╗      ██████╗ ██████╗ ██████╗      ██████╗██████╗  █████╗ ████████╗███████╗██╗███████╗
██║     ██╔═══██╗██╔══██╗██╔══██╗    ██╔════╝██╔══██╗██╔══██╗╚══██╔══╝██╔════╝██║██╔════╝
██║     ██║   ██║██████╔╝██║  ██║    ██║     ██████╔╝███████║   ██║   █████╗  ██║███████╗
██║     ██║   ██║██╔══██╗██║  ██║    ██║     ██╔══██╗██╔══██║   ██║   ██╔══╝  ██║╚════██║
███████╗╚██████╔╝██║  ██║██████╔╝    ╚██████╗██║  ██║██║  ██║   ██║   ███████╗██║███████║
╚══════╝ ╚═════╝ ╚═╝  ╚═╝╚═════╝      ╚═════╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝   ╚══════╝╚═╝╚══════╝
</pre>

# Shivam Tamboli

### `data systems / applied ML / security / strange machines`

B.Tech · **AI, Data Science & Machine Learning**  
Pune, Maharashtra · India

[**shivambuilds.dev**](https://shivambuilds.dev) ·
[**LinkedIn**](https://www.linkedin.com/in/crateis/) ·
[**@LordCrateis**](https://github.com/LordCrateis)

<sub>engineering for autonomy — technical, financial, geographical.</sub>

</div>

---

## `00 / MANIFEST`

I like systems that are **fast, small, explainable and slightly over-engineered for interesting reasons**.

Most of my work lives somewhere between data engineering and applied machine learning: processing ugly datasets, finding signal in scarce data, serving models under annoying infrastructure constraints, and turning notebooks into things that actually run.

I have a particular weakness for:

`Polars` over dataframe bloat · `few-shot learning` · `anomaly detection` · `serverless systems` · `weird interfaces` · `security tooling`

The long game is less complicated:

> become unreasonably good at machine learning, build enough independence to choose my own problems, and eventually take that freedom somewhere very high above sea level.

---

## `01 / THE ENGINE ROOM`

```text
DATA              Python → Polars → PostgreSQL → Spark
ML                scikit-learn → PyTorch → TensorFlow
BOOSTING          XGBoost → LightGBM
EXPERIMENTS       MLflow → Optuna
BACKENDS          FastAPI → Flask
STORAGE           MongoDB → Redis → Neo4j → Cassandra
INFRA             Docker → AWS Lambda → Azure Functions
SECURITY          Nmap → Nuclei → Shodan
DEPLOYMENT        Vercel → Render → Hugging Face
```

I don't treat that list as a Pokémon collection.

Some of it is production experience.  
Some of it is active study.  
All of it has to eventually survive contact with a real project.

### Current technical gravity

**Performance-oriented data work**  
Polars is currently my favorite hammer: columnar execution, vectorization, lazy evaluation, lower memory pressure, and considerably less patience for blindly defaulting to Pandas.

**Machine learning under constraints**  
I'm especially interested in **few-shot learning** and **anomaly detection** — the cases where the dataset is small, weird, imbalanced, incomplete, hostile, or otherwise refuses to behave.

**Lean infrastructure**  
I like designing around constraints instead of pretending they don't exist: serverless execution, memory ceilings, cold starts, cheap hosting, API boundaries, model-loading behavior and deployment architecture.

---

## `02 / SHIPYARD`

Projects explain me better than a paragraph does.

<table>
<tr>
<td width="50%" valign="top">

### ⚕ NutriCore AI

A health-prediction system built around a Gradient Boosting model and exposed through a live Flask application.

The interesting part wasn't merely training the model — it was treating inference like a product: deployment, model loading, latency and user feedback included.

**Built with**

`scikit-learn` `Flask` `Hugging Face Spaces`

**→ [nutricore.shivambuilds.dev](https://nutricore.shivambuilds.dev)**

</td>
<td width="50%" valign="top">

### ⚓ Forty Minutes to Forever

A Titanic survival model disguised as an **interactive-fiction game**.

The player thinks they're making narrative choices aboard an industrial-maritime-punk ocean liner.

The model knows they're selecting features.

`ML × Interactive Fiction`

`scikit-learn` `branching narrative`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ◉ Flamolina

My personal RAG assistant.

Instead of asking a generic model to impersonate me, Flamolina retrieves from a deliberately maintained personal knowledge base and feeds only relevant context into generation.

Built while fighting a **512 MB deployment ceiling**, which made architecture choices much more interesting.

`FastAPI` `Supabase` `Vector Search`  
`Vercel` `Render` `RAG`

</td>
<td width="50%" valign="top">

### ⌖ Asset & Vulnerability Scanner

A scoped reconnaissance pipeline combining passive and active discovery.

Shodan discovers.  
Nmap interrogates.  
Nuclei tests.  
The reporting layer turns the mess into something useful.

Scope enforcement is treated as part of the architecture rather than an afterthought.

`Python` `Nmap` `Nuclei` `Shodan`

</td>
</tr>

<tr>
<td width="50%" valign="top">

### ◫ Olist E-Commerce Analytics

Analysis of **100k+ Brazilian e-commerce orders** across customer behavior, sellers, payments, delivery performance and commercial patterns.

SQL for interrogation.  
Polars for exploration.  
Power BI for communicating the result.

`PostgreSQL` `Polars` `Power BI`

**→ [repository](https://github.com/LordCrateis/olist-ecommerce-analytics)**

</td>
<td width="50%" valign="top">

### ◇ The Portfolio

Not just a place to dump project cards.

It's where the projects, experiments, writing and whatever I become interested in next eventually converge.

The goal is to keep it closer to a **digital workshop** than a conventional developer portfolio.

**→ [shivambuilds.dev](https://shivambuilds.dev)**

</td>
</tr>
</table>

---

## `03 / THE STRANGE LAB`

Not everything I think about fits neatly inside `"production-ready"`.

Some ideas need to remain weird for a while.

### `SAC — Schrödinger's Artificial Consciousness`

A conceptual framework exploring machine state before inference:

> if multiple potential internal responses exist before observation, when — if ever — does the machine's state meaningfully *collapse*?

Less *"is the AI conscious?"*

More *"what exactly exists between stored structure and observed inference?"*

**Status:** `active research / conceptual`

---

### `KANDLE`

A speculative neural-memory system designed around reconstructing experience from fragments:

```text
inner speech
      +
emotional state
      +
visual recall
      +
context
      ↓
 reconstructed memory
      ↓
 lifelike simulation
```

It began as technology inside a screenplay.

Then the technology became interesting enough to escape the screenplay.

---

## `04 / I ALSO WRITE THINGS THAT CANNOT BE IMPORTED`

When I'm not making machines predict things, I tend to make fictional civilizations suffer.

A few inhabitants of the other half of my brain:

**`Rutherford`**  
A science-fiction war built around covert networks, asymmetric resistance and a whispered verification code.

**`Amora`**  
Forbidden love, dogma and generational violence inside the dark-fantasy world of Heraltia.

**`All to Him`**  
Folk horror involving a festival, a deity named Fauma and a sacrifice requirement that probably violates several tourism-board guidelines.

**`Rose of a Lilium`**  
Memory, simulation and a technology called the Kandle Chip.

**`Smithereens`**  
A story about kindness, humiliation and the mathematics of becoming someone worse.

There is also a larger world.

The notes crossed **500 pages** before I was willing to admit it had become a problem.

That is apparently still less than 10% of it.

---

## `05 / BASECAMP`

There is another project running in parallel with all of this.

It doesn't compile.

### THE 20-PEAK REVOLUTION

```text
peak 01 ──┐
peak 02   │
peak 03   │
   ...    ├── progressively harder terrain
peak 20 ──┘
              ↓
        7,000m Himalaya
              ↓
             2028
```

I'm training across twenty increasingly difficult climbs with one distant objective:

**lead and fund a 7,000-metre Himalayan expedition.**

The mountain is useful because it doesn't care about GitHub stars, titles, credentials, plans or confidence.

Either the preparation worked or it didn't.

---

## `06 / CURRENT TRAJECTORY`

```text
NOW
 │
 ├─ sharpen data engineering
 ├─ go deeper into ML
 ├─ build projects that survive deployment
 ├─ learn distributed systems
 ├─ understand models rather than merely calling them
 └─ accumulate technical leverage
          │
          ▼
     AUTONOMY
          │
     ┌────┴────┐
     │         │
   BUILD     EXPLORE
     │         │
     ▼         ▼
research     mountains
systems      travel
stories      Europe
     │         │
     └────┬────┘
          ▼
     keep going
```

A PhD in the AI / ML / data world is somewhere on that horizon too.

Not because `"Dr."` looks good in a bio.

Because I want to eventually reach problems where reading papers isn't enough and **creating new knowledge becomes the job**.

---

## `07 / OPERATING DOCTRINE`

```yaml
optimize_for:
  - independence
  - depth
  - useful obsession
  - difficult projects
  - stories worth remembering

avoid:
  - credential collecting
  - performative productivity
  - unnecessary abstraction
  - "we've always done it this way"
  - pandas when polars can start a fight

default_response_to_uncertainty:
  - build something
  - go somewhere
  - find out
```

---

<details>
<summary><b>Things outside the terminal</b></summary>
<br>

**Cinema**

I keep a Letterboxd because apparently remembering every movie I've ever watched manually is unreasonable.

A film gets a 5/5 from me when it does one of two things:

- makes me cry;
- leaves me standing around afterward thinking, *what the fuck was that?*

---

**Books**

Some permanent residents of the shelf:

- *The Blade Itself*
- *The Eye of the World*
- *The Three-Body Problem*
- *Project Hail Mary*

Fantasy, science fiction, enormous worlds, terrible decisions. The usual.

---

**Elsewhere**

Long late-night walks.  
Spontaneous trips.  
Mountains.  
Photography.  
Travel films.  
Europe whenever bureaucracy permits.

</details>

---

## `08 / STATUS`

```text
location      Pune / Maharashtra / India
role          B.Tech student
domain        AI · Data · ML
username      LordCrateis

building      systems
studying      relentlessly
writing       worlds
training      uphill

final_form    unknown
```

No contribution streak morality.

No `"10x developer"` declaration.

No progress bar pretending a technology can be `████████░░ 80% learned`.

The repositories are the evidence.

---

<div align="center">

### `BUILD → BREAK → UNDERSTAND → REBUILD`

<sub>
My GitHub is a workshop, not a museum.<br>
Things here may be unfinished, rebuilt from scratch, unnecessarily ambitious,<br>
or abandoned after teaching me exactly what I needed from them.
</sub>

<br><br>

[**PORTFOLIO**](https://shivambuilds.dev)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**LINKEDIN**](https://www.linkedin.com/in/crateis/)
&nbsp;&nbsp;·&nbsp;&nbsp;
[**GITHUB**](https://github.com/LordCrateis)

<br><br>

<code>efficiency is useful. freedom is the point.</code>

</div>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:6F00FF,45:171022,100:0D1117&height=6&section=footer" width="100%"/>
