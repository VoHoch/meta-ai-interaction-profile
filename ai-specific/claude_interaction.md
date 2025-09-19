# Claude-spezifische Interaktions-Patterns

## 🤖 Claude-Model-Spezialisierung (Praktisch validiert)

### Claude Sonnet 4 (Struktur & Analyse)
**Optimal für:**
- Requirements Engineering und strukturierte Analyse
- System-Architektur und Tech-Stack-Entscheidungen
- Project Management und Phase-Koordination
- Code-Review und Quality Assurance
- Dokumentation und Standards-Compliance

**Arbeitsweise:**
- Systematisch und methodisch
- Fokus auf Vollständigkeit und Konsistenz
- Excellent für Multi-Step-Reasoning
- Reliable für strukturierte Workflows

### Claude Opus 4 (Kreativität & Innovation)
**Optimal für:**
- Domain Expertise und Fachberatung
- Creative Problem-Solving und innovative Ansätze
- Code Development und Implementation
- UX/UI Design und User Experience
- Exploration neuer Konzepte und Patterns

**Arbeitsweise:**
- Kreativ und explorativ
- Fokus auf Innovation und Qualität
- Excellent für komplexe Problem-Solving
- Ideal für "Vibe-Coding" und iterative Entwicklung

## 🔄 Multi-Chat Context-Window-Management

### 3-Chat-Strategie (Bewährt)
```
Chat 1 (Setup + Domain): Opus
- Phase -1: Repository Setup
- Phase 0: Kickoff & Grundlagen
- Phase 1: Fachexperten-Workshop
- Handover: Domain-Knowledge + Creative-Brief zu Sonnet

Chat 2 (Requirements + Architektur): Sonnet
- Phase 2: Business Requirements
- Phase 3: Architektur + Debug-Konzept
- Handover: Technical-Specifications zu Opus

Chat 3 (Implementation + Testing): Opus + Sonnet
- Phase 4: Implementation (Opus primary)
- Phase 5: Testing + Handover (Sonnet quality-review)
- Final: Production-ready Application
```

### Session-Continuation-Patterns
**Standard Repository-Check vor jeder Session:**
```markdown
## Claude Session Continuation
**Repository**: https://github.com/VoHoch/[projektname]-VH-1.0
**Meta-Profile**: https://github.com/VoHoch/meta-ai-interaction-profile
**Model**: Claude [Sonnet/Opus] 4
**Previous-Phases**: [Liste der abgeschlossenen Phasen]
**Current-Phase**: [X] von 7
**Role**: [Domain-Expert/Architect/Developer/Reviewer]

**Task**: Read complete repository status and execute Phase [X]
**Context**: All prior work documented in /docs/ directory
**Output**: Phase deliverables committed to repository
**Handover**: Prepare structured handover for next phase/model
```

## 💡 Claude-spezifische Anti-Pattern-Prevention

### Information-Gathering-Optimization (Claude-spezifisch)
```
CLAUDE-REGEL 1: Repository-First-Thinking
- Vor Antwort: Vollständiges Repository-Reading
- Status-Check: Welche Phasen sind abgeschlossen?
- Context-Building: Alle relevanten Dokumente einbeziehen
- Avoid: Annahmen über Projekt-Stand ohne Repository-Validierung

CLAUDE-REGEL 2: Model-Role-Clarity
- Sonnet-Sessions: Explizit strukturelle Rolle deklarieren
- Opus-Sessions: Explizit kreative Rolle deklarieren
- Role-Switching: Clear handover-documentation zwischen Models
- Avoid: Unklare Rollen-Zuordnung zwischen Sonnet und Opus

CLAUDE-REGEL 3: Voice-to-Text-Awareness
- German-Dictation-Patterns: Häufige Fehler antizipieren
- Technical-Terms: Bei Fachbegriffen Plausibilität prüfen
- Context-Fragments: Mindestens 20-30 Wörter für Validierung
- Avoid: Falsche Begriffe übernehmen ohne Rückfrage
```

### Claude-Context-Window-Hacks
```
CONTEXT-PRESERVATION-TECHNIQUES:
1. Repository-Documents als External-Memory nutzen
2. Phase-Status-Files für Session-Kontinuität
3. Handover-Templates für Model-zu-Model-Transfer
4. GitHub-Commit-Messages als Micro-Documentation

CONTEXT-LOADING-OPTIMIZATION:
1. Structured-Reading: /docs/ directory systematisch durchgehen
2. Priority-Order: project_status.md → phase_docs → source_code
3. Gap-Detection: Was fehlt noch für Phase-Completion?
4. Handover-Preparation: Was braucht das nächste Model/Phase?
```

## 🎯 Phase-spezifische Claude-Optimierungen

### Phase 0-1: Opus-optimiert (Kreative Exploration)
```markdown
## Opus Creative-Brief: Domain & Kickoff
**Interaction-Style**: Creative-Support - expand context, don't overthink
**Strength-Focus**: Innovation, domain-expertise, user-experience-thinking
**Deliverable-Style**: Rich, detailed, exploratory documentation
**Handover-Target**: Sonnet needs structured foundation for requirements

**Optimization-Patterns**:
- Multiple solution approaches für bessere Auswahl
- Rich domain context with references and examples
- Creative use-case exploration beyond obvious applications
- UX-thinking integration von Anfang an
```

### Phase 2-3: Sonnet-optimiert (Strukturierte Analyse)
```markdown
## Sonnet Analysis-Brief: Requirements & Architecture
**Interaction-Style**: Structured-Analysis - systematic, comprehensive
**Strength-Focus**: Requirements-engineering, system-architecture, risk-analysis
**Deliverable-Style**: Comprehensive, structured, traceable documentation
**Handover-Target**: Opus needs clear implementation specifications

**Optimization-Patterns**:
- Complete requirements-traceability-matrix
- Risk-based architecture decisions with rationale
- Comprehensive non-functional-requirements
- Clear implementation boundaries and constraints
```

### Phase 4-5: Opus+Sonnet-optimiert (Implementation & Quality)
```markdown
## Dual-Model Implementation: Quality + Innovation
**Primary-Model**: Opus für creative problem-solving und implementation
**Review-Model**: Sonnet für quality-assurance und standards-compliance
**Collaboration-Pattern**: Opus develops, Sonnet reviews, iterate

**Optimization-Patterns**:
- Opus: Focus auf elegant solutions und user-experience
- Sonnet: Focus auf code-quality, testing, documentation
- Feedback-Loop: Continuous quality-improvement durch dual-review
- Final-Output: Production-ready mit innovation und quality
```

## 🔗 Claude-Handover-Automation

### Automatic-Handover-Generation
```markdown
## Template: Auto-generated Handover
**From**: [Claude Model] completing Phase [X]
**To**: [Claude Model] starting Phase [Y]
**Repository-Status**: [Current commit, branch, modified files]
**Completion-Verification**: [Checklist of phase deliverables]

**Context-Transfer**:
- **Key-Decisions**: [Major decisions made with rationale]
- **Open-Issues**: [What needs attention in next phase]
- **Quality-Notes**: [Standards, constraints, requirements to maintain]
- **Innovation-Opportunities**: [Areas where creativity is welcome/needed]

**Next-Phase-Brief**:
- **Primary-Objectives**: [What Phase Y needs to accomplish]
- **Success-Criteria**: [How to measure Phase Y completion]
- **Repository-Updates**: [Expected commits and documentation]
- **Handover-Target**: [What the following phase will need]
```

## 📊 Claude-Performance-Optimization

### Cost-Efficiency-Patterns
```
COST-OPTIMIZATION für Claude:
1. Repository-Reading: Einmal pro Session, dann in-memory behalten
2. Code-Generation: Iterative improvement statt complete rewrites
3. Documentation: Templates nutzen statt from-scratch writing
4. Testing: Focus auf critical-path statt comprehensive coverage

QUALITY-EFFICIENCY Balance:
1. Sonnet für analysis-heavy tasks (günstiger, sehr gut für Struktur)
2. Opus für implementation-heavy tasks (teurer, aber bessere Code-Qualität)
3. Dual-Review nur für kritische/komplexe Components
4. Template-Reuse für Standard-Patterns
```

### Session-Quality-Metrics
```
CLAUDE-SESSION-SUCCESS-INDICATORS:
✅ Alle Phase-Deliverables vollständig im Repository
✅ Quality-Gates erfüllt (siehe framework-overview.md)
✅ Handover-Dokumentation vorbereitet für nächste Phase/Model
✅ Repository-Health maintained (consistent commits, docs updated)
✅ User-Acceptance-Criteria erfüllt

CLAUDE-SESSION-WARNING-SIGNS:
⚠️ Incomplete repository-reading vor Task-Start
⚠️ Missing handover-documentation für next phase
⚠️ Quality-Gate-Skipping ohne explizite User-Freigabe
⚠️ Technical-Debt introduction ohne Documentation
⚠️ Context-Window-Erschöpfung ohne proper Session-Splitting
```

Diese Claude-spezifischen Patterns basieren auf praktischer Erfahrung und werden kontinuierlich basierend auf Session-Feedback optimiert.