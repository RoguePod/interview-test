guard :rubocop, all_on_start: true, cli: ['-RD'] do
  watch(/.+\.rb$/)
  watch(/.+\.rake$/)
  watch(/.+\.jbuilder$/)
  watch(/Rakefile$/)
  watch(/Gemfile$/)
  watch(%r{(?:.+/)?\.rubocop\.yml$}) { |m| File.dirname(m[0]) }
end
