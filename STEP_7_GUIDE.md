# Step 7: Port MERGE / Upsert and Write Logic

## 📋 Description

Replace T-SQL MERGE, INSERT, UPDATE statements with Beam sink writes.

## 🎯 Objectives

- Complete step-specific objectives
- Follow best practices
- Document decisions
- Test thoroughly


## ✅ Tasks Checklist

- [ ] Simple INSERT: use JdbcIO.write() or BigQueryIO.write()
- [ ] MERGE (upsert): use JdbcIO.write() with custom PreparedStatementSetter using ON CONFLICT / MERGE SQL in the sink
- [ ] Multi-destination writes: use tagged outputs (TupleTag) to fan out to multiple sinks
- [ ] Dead-letter queue: route failed records to a separate TextIO / BigQuery error table


## 📚 Resources

### Apache Beam (Java SDK) Documentation
- Official documentation
- Framework guides
- Best practices

### Migration Guides
- Language comparison guides
- Framework migration docs
- Community resources

## 🔧 Tools & Setup

### Required Tools


## 📝 Implementation Guide

### Getting Started

1. **Review the tasks**: Read through all tasks in this step
2. **Setup environment**: Ensure all required tools are installed
3. **Follow best practices**: Use coding standards for Apache Beam (Java SDK)
4. **Test frequently**: Run tests after each significant change
5. **Document changes**: Keep notes on decisions and issues

### Tips for Success

- Work incrementally - don't try to do everything at once
- Test early and often
- Keep the original T-SQL code for reference
- Ask for help when stuck
- Document any blockers or issues

## 🐛 Common Issues

### Issue 1: [Common Problem]
**Solution**: [How to solve it]

### Issue 2: [Another Common Problem]
**Solution**: [How to solve it]

## ✅ Definition of Done

This step is complete when:
- [ ] All tasks in checklist are completed
- [ ] Code is tested and passes all tests
- [ ] Documentation is updated
- [ ] Code review is completed
- [ ] Changes are merged to main branch

## 📊 Progress Tracking

Update the progress in `.github/MIGRATION_TRACKING.md` as you complete tasks.

## 🔗 Related Issues

- GitHub Issue #[TBD] - Track this step's progress

## 👥 Team

**Assigned To**: _Unassigned_
**Reviewer**: _TBD_

## 📅 Timeline

**Start Date**: _Not started_
**Target Completion**: _TBD_
**Actual Completion**: _Not completed_

---

**Next Step**: Step 8 (if applicable)

Last Updated: 2026-03-19
