# Kubernetes & DevOps Concept-Based Questions

## Disaster Recovery & Reliability

1. What is RPO (Recovery Point Objective)?

2. What is RTO (Recovery Time Objective)?

3. What is the difference between RPO and RTO?

4. What is MTTR (Mean Time To Recovery)?

5. What is MTBF (Mean Time Between Failures)?

6. What is the difference between MTTR, MTBF, RPO, and RTO?

7. What is a Disaster Recovery (DR) strategy?

8. What is High Availability (HA)?

9. What is Fault Tolerance?

10. What is the difference between High Availability and Fault Tolerance?

11. What is Business Continuity?

12. What is a Disaster Recovery Plan?

13. What is Backup and Restore?

14. What is the difference between backup and replication?

15. What is active-active architecture?

16. What is active-passive architecture?

17. What is a DR site?

18. What is failover?

19. What is failback?

---

## Reliability & Service Management

20. What is an SLA (Service Level Agreement)?

21. What is an SLI (Service Level Indicator)?

22. What is an SLO (Service Level Objective)?

23. What is the difference between SLA, SLO, and SLI?

24. What is an Error Budget?

25. How is an Error Budget related to SLO?

26. What is uptime?

27. How do you calculate availability?

28. What does 99.9% availability mean?

29. What does 99.99% availability mean?

30. What is the difference between availability and reliability?

---

## Kubernetes Core Concepts

31. What is a Pod?

32. What is a ReplicaSet?

33. What is a Deployment?

34. What is a StatefulSet?

35. What is a DaemonSet?

36. What is a Job?

37. What is a CronJob?

38. What is a Namespace?

39. What is a Label?

40. What is a Selector?

41. What is an Annotation?

42. What is a ServiceAccount?

43. What is a ConfigMap?

44. What is a Secret?

45. What is a ResourceQuota?

46. What is a LimitRange?

47. What is a PodDisruptionBudget?

---

## Kubernetes Scheduling

48. What is Kubernetes scheduling?

49. What is a Node Selector?

50. What is Node Affinity?

51. What is Pod Affinity?

52. What is Pod Anti-Affinity?

53. What are Taints and Tolerations?

54. What is the difference between Node Affinity and Taints/Tolerations?

55. What is a Topology Spread Constraint?

56. How does Kubernetes decide where to schedule a Pod?

57. Why would a Pod remain in Pending state?

---

## Kubernetes Resources

58. What are CPU and memory requests?

59. What are CPU and memory limits?

60. What is the difference between requests and limits?

61. What happens when a container exceeds its memory limit?

62. What is OOMKilled?

63. What is CPU throttling?

64. Why are resource requests important for Kubernetes scheduling?

65. How do you calculate appropriate resource requests and limits?

---

## Kubernetes Storage

66. What is Persistent Volume (PV)?

67. What is Persistent Volume Claim (PVC)?

68. What is StorageClass?

69. What is dynamic provisioning?

70. What is static provisioning?

71. What is the difference between ephemeral and persistent storage?

72. What is a VolumeSnapshot?

73. What happens to a PVC when a Pod is deleted?

74. What happens to persistent data when a Worker Node fails?

---

## Kubernetes Networking

75. What is Kubernetes networking?

76. What is Pod-to-Pod communication?

77. What is Pod-to-Service communication?

78. What is Service discovery?

79. What is Kubernetes DNS?

80. What is ClusterIP?

81. What is NodePort?

82. What is LoadBalancer?

83. What is Ingress?

84. What is an Ingress Controller?

85. What is a NetworkPolicy?

86. What is CNI?

87. What is the difference between Ingress and LoadBalancer?

---

## Kubernetes Security

88. What is RBAC?

89. What is the principle of least privilege?

90. What is a ServiceAccount?

91. What is a Role?

92. What is a ClusterRole?

93. What is a RoleBinding?

94. What is a ClusterRoleBinding?

95. What is Pod Security?

96. What is a SecurityContext?

97. What is a non-root container?

98. What is image vulnerability scanning?

99. What is Kubernetes NetworkPolicy?

100. How do you secure communication between Kubernetes services?

---

## Kubernetes Observability

101. What is Monitoring?

102. What is Logging?

103. What is Tracing?

104. What is Observability?

105. What is the difference between Monitoring and Observability?

106. What are the three pillars of observability?

107. What are Metrics?

108. What are Logs?

109. What are Traces?

110. What is Prometheus?

111. What is Grafana?

112. What is Alertmanager?

113. What is centralized logging?

114. What is distributed tracing?

---

## CI/CD & GitOps

115. What is CI?

116. What is CD?

117. What is Continuous Delivery?

118. What is Continuous Deployment?

119. What is the difference between Continuous Delivery and Continuous Deployment?

120. What is GitOps?

121. What is the GitOps source of truth?

122. What is Argo CD?

123. What is the difference between CI/CD and GitOps?

124. What is Infrastructure as Code?

125. What is Immutable Infrastructure?

126. What is configuration drift?

127. What is reconciliation in GitOps?

---

## Deployment Strategies

128. What is Rolling Deployment?

129. What is Blue-Green Deployment?

130. What is Canary Deployment?

131. What is Recreate Deployment?

132. What is the difference between Blue-Green and Canary Deployment?

133. What is Zero-Downtime Deployment?

134. What is a Rollback?

135. What is a Rollforward?

136. What is Progressive Delivery?

---

## Scaling

137. What is Horizontal Scaling?

138. What is Vertical Scaling?

139. What is Horizontal Pod Autoscaler?

140. What is Vertical Pod Autoscaler?

141. What is Cluster Autoscaler?

142. What is Karpenter?

143. What is the difference between HPA, VPA, and Cluster Autoscaler?

144. When would you use horizontal scaling instead of vertical scaling?

---

## Containers

145. What is a container?

146. What is a container image?

147. What is a Dockerfile?

148. What is an image layer?

149. What is a container registry?

150. What is the difference between an image and a container?

151. What is a multi-stage Docker build?

152. What is a container runtime?

153. What is the difference between Docker and Kubernetes?

154. Why should containers be immutable?

---

## Production Troubleshooting Concepts

155. What is a CrashLoopBackOff?

156. What is ImagePullBackOff?

157. What is ErrImagePull?

158. What is a Pending Pod?

159. What is a Terminating Pod?

160. What is a Failed Pod?

161. What is a readiness failure?

162. What is a liveness failure?

163. What is a node NotReady state?

164. What is resource pressure?

165. What is memory pressure?

166. What is disk pressure?

167. What is configuration drift?

168. What is a single point of failure (SPOF)?

169. How do you identify the root cause of a production incident?

170. What is a post-incident review?

171. What is a Root Cause Analysis (RCA)?
