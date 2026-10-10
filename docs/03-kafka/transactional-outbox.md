# Transactional Outbox

> **Study note:** A structured revision starter based on the topics discussed. Expand this page with your own code and detailed lesson notes.

## What it means

Save the business record and outbox event in one database transaction. A publisher sends pending events and marks them complete. If publishing succeeds but marking fails, duplicates are possible.

## How to approach it

1. **Define the problem.** State what this concept solves and the assumptions.
2. **Explain the mechanism.** Describe the components and their interaction.
3. **Give a practical example.** Relate it to a Java/Spring Boot application or production system.
4. **Discuss trade-offs.** Cover performance, reliability, consistency, complexity and maintenance.
5. **Test edge cases.** Include failure paths, concurrency and recovery where applicable.

## Key points to remember

- Describe broker/topic/partition mechanics, delivery and offset handling, consumer failure recovery and operational trade-offs.
- State limitations instead of claiming the pattern or technology solves every problem.
- Support design decisions with concrete measurements or failure scenarios.

## Interview practice

**Question:** Compare polling, CDC and immediate post-commit publishing with fallback.

**Answer framework:** Start with the core principle, walk through a concrete example, explain the trade-offs, and finish with how you would test or monitor it.

## Personal revision notes

- [ ] Reviewed the concept
- [ ] Explained it without looking
- [ ] Practised an example
- [ ] Answered the interview question

