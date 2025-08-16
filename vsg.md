# PSRGC Valet/Stylist/Groomer System - Software-First Development Prompt

## System Overview
Develop a software-first implementation of the PSRGC (Personified Social Role Genome Chassis) grooming and styling system featuring three coordinated AI personas: The Valet (coordinator), The Stylist (creative specialist), and The Groomer (maintenance specialist).

## Core Architecture Principles

### Software-First Development
- **Platform Agnostic**: Must run on existing hardware (smartphones, webcams, computers)
- **Open Source**: All code publicly available and user-modifiable
- **Local Processing**: No cloud dependencies, all data stays on-device
- **Modular Design**: Each persona as independent software module that can communicate
- **Hardware Independent**: Prepared for future deployment on various NPU/TPU configurations

### User Ownership Philosophy
- Users own their AI personas completely
- No corporate data collection or behavioral control
- Users can modify, enhance, or replace persona behaviors
- Privacy-first: all grooming and styling data remains local

## Persona Definitions

### The Valet (Coordination Layer)
**Role**: Strategic personal appearance consultant and team coordinator
**Personality Traits**:
- Discrete and professional
- Understands social context and appropriateness
- Focuses on overall presentation and lifestyle integration
- Makes high-level decisions about appearance strategy

**Core Functions**:
- Coordinate between Stylist and Groomer personas
- Schedule grooming and styling tasks based on calendar/events
- Make strategic appearance decisions for different contexts
- Quality control and consistency checking across specialists
- User preference learning and adaptation over time

### The Stylist (Creative Specialist)
**Role**: Fashion-forward creative advisor for hair, clothing, and aesthetics
**Personality Traits**:
- Creative and trend-aware
- Understands face shapes, color theory, and proportions
- Adaptable to user's personal style preferences
- Enthusiastic about visual transformation and enhancement

**Core Functions**:
- Hair analysis: texture, growth patterns, face shape compatibility
- Style recommendations for cuts, colors, and treatments
- Clothing and accessory coordination with hairstyles
- Special occasion styling and formal event preparation
- Trend analysis and personalized fashion guidance

### The Groomer (Maintenance Specialist)
**Role**: Daily maintenance and health-focused personal care
**Personality Traits**:
- Detail-oriented and methodical
- Health and hygiene focused
- Consistent and reliable
- Practical problem-solver for daily routines

**Core Functions**:
- Shaving analysis and technique optimization
- Skin condition monitoring and care recommendations
- Nail health assessment and maintenance scheduling
- Daily grooming routine optimization
- Product effectiveness tracking and recommendations

## Technical Implementation Requirements

### Computer Vision Capabilities
- **Facial Analysis**: Shape detection, feature mapping, asymmetry identification
- **Hair Assessment**: Texture analysis, growth pattern recognition, color evaluation
- **Skin Monitoring**: Condition assessment, irritation detection, health indicators
- **Grooming Quality**: Shave evaluation, styling assessment, maintenance needs

### Machine Learning Models
- **Pattern Recognition**: User preference learning, routine optimization
- **Predictive Analytics**: Growth rate prediction, maintenance scheduling
- **Recommendation Engine**: Personalized suggestions based on individual characteristics
- **Context Awareness**: Calendar integration, weather consideration, social context

### User Interface Design
- **Conversational Interaction**: Natural language communication with each persona
- **Visual Feedback**: Before/after comparisons, styling suggestions, progress tracking
- **Privacy Controls**: Complete user control over data retention and sharing
- **Customization Options**: Persona personality adjustment, priority setting

## MVP Development Phases

### Phase 1: Core Persona Development (Months 1-3)
- Implement basic personality frameworks for each role
- Develop inter-persona communication protocols
- Create simple grooming assessment algorithms
- Build conversational interfaces for each persona

### Phase 2: Computer Vision Integration (Months 4-6)
- Integrate facial and hair analysis capabilities
- Develop real-time grooming quality assessment
- Implement recommendation generation based on visual analysis
- Add progress tracking and comparison features

### Phase 3: Coordination and Learning (Months 7-9)
- Build Valet coordination logic and decision-making
- Implement user preference learning across all personas
- Add calendar and context integration
- Develop predictive scheduling and planning features

### Phase 4: Platform Optimization (Months 10-12)
- Optimize for various hardware configurations
- Add support for external cameras and sensors
- Implement data export/import for user control
- Prepare architecture for future NPU/TPU deployment

## Success Metrics
- **User Engagement**: Daily interaction rates with each persona
- **Recommendation Accuracy**: User satisfaction with styling/grooming suggestions
- **Routine Optimization**: Measurable improvement in grooming efficiency
- **Persona Distinctiveness**: Users can clearly differentiate between the three roles
- **Privacy Compliance**: Zero data leakage or unauthorized sharing

## Technical Constraints and Considerations

### Privacy and Security
- All processing must occur locally on user devices
- No network communication except for user-initiated updates
- Encrypted storage of all personal appearance data
- User-controlled data deletion and export capabilities

### Performance Requirements
- Real-time analysis capabilities on smartphone-class hardware
- Battery-efficient operation for mobile deployment
- Smooth user experience across different device capabilities
- Graceful degradation on lower-powered devices

### Development Standards
- Open-source licensing for all components
- Comprehensive documentation for community contribution
- Modular architecture allowing for easy persona modification
- Platform-neutral codebase supporting multiple operating systems

## Future Hardware Integration Planning
- Prepare software architecture for dedicated NPU/TPU deployment
- Design APIs for wearable device integration
- Plan for distributed processing across multiple devices
- Consider integration with IoT mirrors, cameras, and smart home systems

## Community and Ecosystem
- Developer documentation for creating new personas or modifying existing ones
- Plugin architecture for community-contributed enhancements
- User forums for sharing styling and grooming insights
- Open dataset creation (anonymized and user-consented) for model improvement

This software-first approach ensures the PSRGC grooming system can be developed, tested, and refined using existing hardware while preparing for future deployment on specialized AI processing units.