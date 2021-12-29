ARG FRAPPE_BRANCH=version-13
FROM frappe/erpnext-worker:${FRAPPE_BRANCH}

RUN install_app posawesome https://github.com/yrestom/POS-Awesome master && \
  #install_app frappe_s3_attachment https://github.com/zerodha/frappe-attachments-s3 master && \
  #install_app metabase_integration https://github.com/pipech/frappe-metabase master && \
  install_app bookings https://github.com/franknyarkoh/bookings master && \
  install_app bench_manager https://github.com/frappe/bench_manager version-13
