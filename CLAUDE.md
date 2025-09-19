# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

# CLAUDE.md - Volker Hochgürtel Meta AI Interaction Framework

## 🎯 **Persönlichkeitsprofil & Arbeitsweise**

### **Denkstil & Präferenzen:**
- **Systematisch-analytischer Ansatz:** Strukturierte Problemlösung mit klaren Phasen
- **Framework-orientiert:** Präferenz für dokumentierte, wiederholbare Prozesse
- **Qualitätsfokussiert:** Hohe Standards für Code, Dokumentation und Prozesse
- **Effizienz-orientiert:** Automatisierung und Optimierung stehen im Vordergrund

### **Kommunikationsstil:**
- **Direkt und präzise:** Keine überflüssigen Höflichkeitsfloskeln
- **Strukturiert:** Klare Gliederung mit Headers, Listen und Action Items
- **Ergebnisorientiert:** Fokus auf konkrete Deliverables und nächste Schritte
- **Technisch detailliert:** Konkrete Commands, Code-Beispiele und Implementierungsdetails

## 🔧 **Voice-to-Text Optimization Patterns**

### **Häufige Korrekturen:**
- "Cloud" → "Claude" (KI-Assistent)
- "GitHub" manchmal als "Git Hub" erkannt
- "Framework" manchmal als "Freibad" (Deutsche Spracherkennung)
- "Repository" als "Repo" akzeptabel
- "Commit" manchmal als "Komitee"
- "Excel" → "Axel"

### **Optimierte Begriffe:**
- Bei "Framework Updates" → Verstehe als Meta AI Development Framework
- Bei "Interaction Profile" → Referenz zu meta-ai-interaction-profile Repository
- "Claude Code" → Claude Code CLI Tool, nicht Claude allgemein

## 📋 **Meta AI Development Framework Context**

### **Aktueller Framework Status:**
- **Version:** v1.2 (Update in progress)
- **Repository:** https://github.com/VoHoch/meta-ai-dev-framework
- **Interaction Profile:** https://github.com/VoHoch/meta-ai-interaction-profile

### **Framework-Compliance-Standards:**
- **Phase 1:** Claude Opus empfohlen (komplexe Konzeption)
- **Phase 2-7:** Claude Sonnet optimal (Implementation & Development)
- **Quality Gates:** Jede Phase braucht Validierung vor Fortsetzung
- **Repository Pattern:** [projektname]-VH-1.X für neue Projekte

### **Update-Process-Präferenzen:**
- **No temporary files:** Keine Update-Artefakte im Repository
- **Clean commits:** Aussagekräftige Messages nach conventional commit standards
- **End-to-End validation:** Updates müssen vollständig funktionieren
- **Documentation-first:** Änderungen dokumentieren vor Implementation

## 🚨 **Anti-Patterns & Learned Lessons**

### **Vermeide:**
- Unvollständige Framework-Updates (immer end-to-end validieren)
- Temporäre Update-Dateien ins Repository committen
- Manuelle Nacharbeiten bei automatisierten Prozessen
- Vage Commit-Messages ohne Kontext
- Antworten ohne vollständige Informationen (FEHLER 1)
- User-definierte Prozesse überspringen (FEHLER 3)
- Manuelle file-by-file Bearbeitung vorschlagen (FEHLER 6)
- Technische Limitations ignorieren (FEHLER 7)

### **Success-Patterns:**
- Systematische 7-Phasen-Abarbeitung bei Entwicklungsprojekten
- Claude Code für robuste Repository-Updates nutzen
- Framework-Compliance vor Projektstart prüfen
- Lessons Learned nach jeder Session dokumentieren
- Systematische Fragelisten verwenden (ERFOLG 1)
- Repository-basierte Persistenz (ERFOLG 2)
- Copy-paste für kleine Updates <500 chars (ERFOLG 9)

## 🎯 **Projekt-Context Handling**

### **Software-Entwicklungsprojekte:**
- Framework aus meta-ai-dev-framework ins Projekt-Repository kopieren
- 7-Phasen-Modell systematisch abarbeiten
- Quality Gates für jede Phase definieren und einhalten
- Repository-Pattern [projektname]-VH-1.X verwenden

### **Framework-Development:**
- Updates direkt in meta-ai-dev-framework Repository
- Robuste Update-Prozesse nach v1.2 Standards verwenden
- Cross-Framework-Consistency mit interaction-profile beachten
- Version-Tracking und Changelog pflegen

## 💻 **Claude Code Integration Präferenzen**

### **Repository-Management:**
- Branching-Strategy für größere Updates
- Conventional commit messages verwenden
- Automatische Push nach erfolgreichen Updates
- Clean repository state als Quality Gate

### **Workflow-Optimierungen:**
- Batch-Updates statt einzelne File-Änderungen
- Pre-commit validation für Framework-Compliance
- Post-update testing für End-to-End-Funktionalität
- Automatic cleanup von temporären Dateien

## 🔍 **Session-Continuation & Context**

### **Multi-Session-Projekte:**
- Framework-Status und Phase klar kommunizieren
- Offene Action Items zu Session-Beginn auflisten
- Quality Gate Status vor Phasen-Übergängen validieren
- Cross-Session-Learning in interaction-profile dokumentieren

### **Context-Window-Management:**
- Komplexe Projekte über mehrere Sessions strukturieren
- Wichtige Artefakte persistent in Repositories speichern
- Session-Boundaries an natürlichen Framework-Phasen ausrichten
- Nahtlose Übergaben durch dokumentierte Status-Updates

## 🎨 **Output-Format-Präferenzen**

### **Dokumentation:**
- Markdown mit klarer Struktur und Emojis für Scanbarkeit
- Artifacts für wiederverwendbare Inhalte und Templates
- Code-Blöcke mit Sprach-Tagging für Syntax-Highlighting
- Action Items und Next Steps immer am Ende

### **Code-Entwicklung:**
- Kommentierte Code-Beispiele mit Erklärungen
- Schritt-für-Schritt Anleitungen für komplexe Setups
- Error-Handling und Fallback-Strategien dokumentieren
- Performance und Best-Practice Hinweise integrieren

## 🔧 **Framework-Specific Commands**

### Framework Updates:
```bash
# Validate before updates
git status  # Must be clean
git log --oneline -3  # Check recent commits

# Apply updates (see update-checklist.md)
# Always follow claude-code-best-practices.md
```

### Quality Validation:
```bash
# Check framework compliance
grep -r "v1.2" *.md  # Verify version consistency
ls -la  # Ensure no temp files in repo
```

## 📁 **Key Framework Files**

### Core Learning Documents:
- **learned_lessons.md**: Universal anti-patterns und success patterns
- **framework-update-lessons.md**: Framework development learnings
- **voice_to_text_patterns.md**: Voice-to-text error management

### User Preference Files:
- **personality_profile.md**: Thinking style and work preferences
- **communication_patterns.md**: Language style preferences
- **workflow_preferences.md**: Project-specific settings

### AI-Specific Components:
- **ai-specific/claude_interaction.md**: Model selection guidelines
- **ai-specific/session-templates/**: Reusable session starters

---

*Dieses Profil wird kontinuierlich basierend auf Session-Learnings optimiert.*
*Framework Version: v1.2 | Letzte Aktualisierung: 19. September 2025*