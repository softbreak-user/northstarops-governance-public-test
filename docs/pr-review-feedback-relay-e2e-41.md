# PR Review Feedback Relay E2E Test

Bu dosya NorthStarOps governance PR Review Feedback Relay E2E testi için oluşturulmuştur.

Test Issue: #41

## Amaç

Fork-origin Pull Request review eventlerinin güvenli iki aşamalı relay üzerinden private governance katmanına taşındığını doğrulamak.

## Doğrulanacak akış

- Draft PR Admission
- Ready for review geçişi
- Request Changes review
- Secretsiz review payload capture
- Artifact upload
- Trusted workflow_run relay
- Private repository_dispatch
- Changes Requested feedback
- Aynı branch ve aynı PR üzerinden düzeltme
- Approval feedback
