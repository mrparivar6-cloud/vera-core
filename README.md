# VERA — Verifiable Reference Authority

VERA is a vendor-neutral reference authority system designed to provide
verifiable, timestamped attribution of inputs, statements, and declarations.

VERA does not make decisions, provide advice, execute actions, or perform
automation of any kind.

## Internal Architecture

VERA incorporates an internal mechanism referred to as the
Decision Attribution Layer (DAL).

DAL is not a separate product or service.
It is an internal technical layer responsible solely for:
- metadata normalization
- timestamping
- hashing
- immutable reference logging

DAL does not evaluate, judge, or validate correctness.
Its role is strictly attribution and reference preservation.

## Authority Model

VERA operates in Silent Authority Mode.

All outputs are reference records, not recommendations or commands.
Any downstream system (bots, agents, traders, guardians) operates independently
and consumes VERA references at its own risk.

## Legal Position

VERA is a reference and attribution system only.
It does not provide financial, legal, medical, or operational advice.
Responsibility for interpretation or action lies entirely with the user or
integrating system.

## Purpose

The purpose of VERA is to establish public, verifiable proof of
existence, attribution, and reference for informational inputs
without asserting control, intelligence, or intent.
