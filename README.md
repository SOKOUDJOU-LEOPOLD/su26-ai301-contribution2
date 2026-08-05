# su26-ai301-contribution2

# Contribution [2]: Add X/Y/Z Text Labels to Coordinate Axes for Colorblindness Accessibility

**Contribution Number:** 2  
**Student:** Leopold Sokoudjou Gatsing  
**Issue:** https://github.com/OpenChemistry/avogadrolibs/issues/1667  
**Status:** Phase I Complete

---

## Why I Chose This Issue

I chose this issue because it has exactly the right scope for a meaningful first contribution: the entire axes feature lives in a single plugin file (`overlayaxes.cpp`), and the text rendering infrastructure I need — `TextLabel3D`, `TextProperties`, `TextLabelBase` — already exists in the codebase. Rather than building a feature from scratch or navigating a massive unfamiliar system, I can focus on learning how to extend an existing rendering pipeline with a clearly defined, self-contained change. The issue is also well-specified: add "x", "y", "z" labels at the tips of the colored coordinate arrows, in matching colors. There is no ambiguity about what success looks like, and there are no competing pull requests, so my work will not be preempted.

Beyond the technical scope, I was drawn to the accessibility motivation. The current axes rely entirely on color (red, green, blue) to distinguish X, Y, and Z, a design that fails entirely for colorblind users. This is a real usability gap in a scientific tool used by chemists, materials scientists, and researchers. Contributing a fix means improving the experience for a concrete group of people who depend on the software. It also gives me hands-on experience with C++, Qt6, CMake, and OpenGL rendering concepts specifically render passes, overlay viewports, and the visitor pattern which are skills I want to develop in a real-world codebase rather than a tutorial project.

---

## Understanding the Issue

### Problem Description

[In your own words, what's broken or missing?]

### Expected Behavior

[What should happen?]

### Current Behavior

[What actually happens?]

### Affected Components

[Which parts of the codebase are involved?]

---

## Reproduction Process

### Environment Setup

[Notes on setting up your local development environment - challenges you faced, how you solved them]

### Steps to Reproduce

1. [Step 1]
2. [Step 2]
3. [Observed result]

### Reproduction Evidence

- **Commit showing reproduction:** [Link to commit in your fork]
- **Screenshots/logs:** [If applicable]
- **My findings:** [What you discovered during reproduction]

---

## Solution Approach

### Analysis

[Your analysis of the root cause - what's causing the issue?]

### Proposed Solution

[High-level description of your fix approach]

### Implementation Plan

Using UMPIRE framework (adapted):

**Understand:** [Restate the problem]

**Match:** [What similar patterns/solutions exist in the codebase?]

**Plan:** [Step-by-step implementation plan]

1. [Modify file X to do Y]
2. [Add function Z]
3. [Update tests]

**Implement:** [Link to your branch/commits as you work]

**Review:** [Self-review checklist - does it follow the project's contribution guidelines?]

**Evaluate:** [How will you verify it works?]

---

## Testing Strategy

### Unit Tests

- [ ] Test case 1: [Description]
- [ ] Test case 2: [Description]
- [ ] Test case 3: [Description]

### Integration Tests

- [ ] Integration scenario 1
- [ ] Integration scenario 2

### Manual Testing

[What you tested manually and results]

---

## Implementation Notes

### Week [X] Progress

[What you built this week, challenges faced, decisions made]

### Week [Y] Progress

[Continue documenting as you work]

### Code Changes

- **Files modified:** [List]
- **Key commits:** [Links to important commits]
- **Approach decisions:** [Why you chose certain approaches]

---

## Pull Request

**PR Link:** [GitHub PR URL when submitted]

**PR Description:** [Draft or final PR description - much of the content above can be adapted]

**Maintainer Feedback:**

- [Date]: [Summary of feedback received]
- [Date]: [How you addressed it]

**Status:** [Awaiting review / Iterating / Approved / Merged]

---

## Learnings & Reflections

### Technical Skills Gained

[What you learned technically]

### Challenges Overcome

[What was hard and how you solved it]

### What I'd Do Differently Next Time

[Reflection on your process]

---

## Resources Used

- [Link to helpful documentation]
- [Tutorial or Stack Overflow post that helped]
- [GitHub issues or discussions that helped]
