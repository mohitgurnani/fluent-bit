set(src
  opentelemetry.c
  opentelemetry_logs.c
  opentelemetry_utils.c
  opentelemetry_conf.c
  )

FLB_PLUGIN(out_opentelemetry "${src}" "")
