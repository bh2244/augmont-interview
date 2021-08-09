# <center>Augmont Gold - Backend Technical Exercise</center>

Thanks for interviewing with us @ Augmont Gold, to better assess your skills and experience, we would like you to take this short technical exercise.

Please follow the following instructions to complete your exercise.

1. Create a new private repository (GitHub) for your exercise and add `bh2244` as private collaborators.
2. Complete as much of the exercise as you can in 4 hours or less. Use Angular technology.
3. Be sure to include the following in your submission

- a README.md with the following information
  - A few screenshots of the finished product. Show off that work!
  - A short explanation of what you built
  - How to test/demo/run (if applicable)
    - NOTE: a 'working' exercise is awesome, however it is NOT a hard requirement. We mean it!
  - Any feedback/notes (i.e. if something was hard, confusing, frustrating, etc)
  - Anything else you'd like us to know about your submission
- a ROADMAP.md with what you would add/change if you had more time. Dream big.
- a super-simple test suite if applicable (even one test is a bonus)
- Some form of lightweight technical documentation (code comments are fine)

4. When complete email a link to the repository and any special instructions back to me.

---

🚨 ❗ 👉 Please use one of the attached salary datasets provided here for this exercise 👈 ❗ 🚨

## Exercise: Expose an API for querying compensation data

The goal of this exercise is to design a read-only API (REST or GraphAPI) that returns one or more records from a static set of compensation data.

**User Story:** _As a developer I want to list compensation data via API GET request_

- Filter by one or more fields/attributes (e.g. `/compensation_data?salary[gte]=120000&zip_code=11201`)

- Sort by one or more fields/attributes (e.g. `/compensation_data?sort=last_name`) fetch a single record via GET request

**Stretch Goal:** return a sparse fieldset (e.g. `/compensation_data?fields=first_name,last_name,salary`) have the JSON response be normalized into a uniform schema via a serializer or json template

**Stretch Goal:** serialize more than one compensation

**A few quick notes on submitting your exercise**

Don't worry about any web application concerns other than serializing JSON and returning via a GET request.

The example above (`/compensation_data...`) is not a contract. Feel free to design the URL structure and JSON schema that you believe creates the best client/consumer experience

## Datasets

[Compensation Salary Data Sets](./salary_datasets/)
