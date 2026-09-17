# Patch notes the council must track

Source: official Steam news + community reports. Last checked 2026-09-17.

## Patch 1.6.2f1 — Autumn Breeze (15 Sep 2026)

Live as of this study. Affects council behavior:

- **Garbage trucks smarter**: reserve capacity for destination, skip buildings with tiny garbage. Fewer false "garbage piling" alerts.
- **Garbage now hits happiness harder**. Uncollected trash is a bigger well-being brake than before. Welfare must not ignore the dump.
- **Company renting priority**: businesses producing the city's most-needed resources rent first. Mayor cannot force a useless factory into a shop slot.
- **Residential demand** now scales with city size. Large cities no longer falsely show zero housing demand.
- **Citizen money uses income, not wealth**, for happiness / shopping / leisure. A rich-but-broke cim shops less.
- UI framework refresh — some mods may break. NDC bridge was built on 1.6.0f1; verify DLL match before first live save.
- Old saves load fine.

## Death wave status

Iceflake shipped a death-wave fix: deaths now calculated 16 times per day instead of in big lumps, so the mass-death spike is reduced. Still avoid zoning one giant residential batch — staggered batches remain the safe play.

## Still broken / watch

- Mail / post offices remain unreliable per community reports.
- Roundabouts are a gamble; sometimes work, sometimes cars swerve.
- Traffic still the top cash-killer when a jam forms.

## Council rule from this patch

Do not treat garbage as a low-priority service. Since 1.6.2f1 it directly tanks happiness, which tanks XP, which stalls milestones. Keep the dump sized and the trucks routed.
