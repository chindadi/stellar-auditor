# Stellar Auditor - Development Plan

## Project Overview
**stellar-auditor** is a professional static analysis tool for Soroban smart contracts that detects expensive patterns and resource inefficiencies before deployment.

## Current Status
- ✅ 40+ production-ready lints implemented
- ✅ Full AST-based analysis framework
- ✅ GitHub Actions integration
- ✅ Docker containerization
- ✅ Comprehensive documentation

## Q1 2026 Roadmap

### Phase 1: Foundation (Weeks 1-4)
- **Code Quality:** Refactor lint registry for extensibility
- **Testing:** Increase UI test coverage to 95%
- **Documentation:** Standardize lint documentation format
- **Performance:** Optimize AST traversal for large codebases

### Phase 2: Feature Expansion (Weeks 5-8)
- **New Lints:** Add 10-15 high-impact pattern detectors
- **Configuration:** Implement per-file lint suppression
- **IDE Support:** Enhance VS Code extension functionality
- **Metrics:** Add linter performance benchmarking

### Phase 3: Ecosystem Integration (Weeks 9-12)
- **CI/CD:** Expand GitHub Actions capabilities
- **Reporting:** JSON/HTML export formats
- **Tooling:** Create cargo-cost-lint v1.0 release
- **Community:** Establish custom lint development guide

## Technical Priorities

| Priority | Area | Goal |
|----------|------|------|
| High | Lint Accuracy | >99% pattern detection rate |
| High | Performance | <2s analysis for typical contract |
| High | Documentation | Every lint has usage examples |
| Medium | Testing | 90%+ code coverage |
| Medium | Accessibility | Cross-platform support |
| Low | UI | Web dashboard (future) |

## Success Metrics
- **Adoption:** 50+ active users in Soroban ecosystem
- **Quality:** Zero false positives reported per release
- **Performance:** Average linting time <1.5 seconds
- **Community:** 10+ community-contributed lints

## Risk Mitigation
- **Rust Version Changes:** Pin toolchain version in CI
- **Breaking Changes:** Semantic versioning with deprecation period
- **Security:** Automated dependency audits (daily)
- **Maintenance:** Clear issue triage and prioritization

## Next Steps
1. Release v0.2.0 with 5 new lints
2. Establish community contribution guidelines
3. Create comprehensive lint plugin SDK
4. Plan production readiness for v1.0
