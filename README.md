# dio-azure11

Governança
Azure Policy
Impor padrões organizacionais e avaliar a conformidade em escala.
Ele fornece governança e consistência de recursos com conformidade regulatória, segurança, custos e gerenciamento.
Exemplo: define por exemplo região onde pode atuar, independentemente do nível do usuário, até mesmo para o administrador.
Você pode fazer uma política e deixar ativada ou desativada.

⚠️ Non-compliant: significa que um recurso não está em conformidade com a regra definida pela política. Exemplo: você criou uma máquina virtual em uma região que não é permitida pela política — esse recurso será marcado como non-compliant.
🔧 Remediation: é o processo de corrigir automaticamente os recursos que estão fora de conformidade. Se a política permitir, o Azure pode ajustar o recurso para ficar de acordo com a regra (por exemplo, aplicar uma tag obrigatória que estava faltando).
✅ Compliant: significa que o recurso está em conformidade com a política. Ou seja, ele segue todas as regras definidas e não precisa de ajustes.
Bloqueio de Recursos
Proteja os recursos do Azure de exclusão ou modificação acidental.
Gerencia bloqueios na assinatura, grupo de recursos ou níveis de recursos individuais dentro do Portal.
Bloqueios são herdáveis.
Excluir: pode ler e atualizar, so nao excluir
ReadOnly - pode ler, não pode atualizar, não pode excluir
Portal de Confiança do Serviço
Permite identificar as regras e políticas da MS quanto as empresas e governos.
MS Purview
Gerencia governança, risco e conformidade.
Reúne insights sobre os dados locais, multinuvem e de software como serviço
