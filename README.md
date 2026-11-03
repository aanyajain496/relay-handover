Relay: evidence-first knowledge handover

Relay rebuilds a project's state from authorised sources and produces a
cited, reviewed, role-based handover when someone leaves a team.

Live demo: https://aanyajain496.github.io/relay-handover/

How to try it
1. Sources: review the synthetic demo project "Orion" (or add your own).
2. Extract and review: each claim shows a status (Verified / Inferred /
   Conflicting) and its source line. Reject the wrong rate-limit claim,
   approve the rest, then publish.
3. Handover: switch between Approver, Incoming lead and New volunteer.

What works (Round 2)
- Redaction of keys, phones and emails on ingestion
- Rules-based claim extraction with evidence links
- Conflict detection, gap list, human approve/reject/edit
- Versioning, receipt confirmation, role-based views, Markdown export
- Optional AI claim proposals with a quote check (works only inside the
  Claude environment; the hosted version uses the rules extractor)

Limitations
- Data is stored in the browser; role filtering runs in the page, so this
  demonstrates the permission design but is not real security.
- No live GitHub connector yet.

Round 3 plan
1. Leaver gap interview
2. GitHub connector plus PDF/DOCX parsing
3. Server-side access control, audit log and readiness score

AI disclosure
Built with AI coding assistance (Claude). All demo data is synthetic.
